<b> Synapse Matrix homeserver setup on a Debian VM. </b>

0_PrepareMachine

1-Prepare the Debian system with a new user, upgrades, and enables SSH.
2-Install and configures PostgreSQL database for Synapse.
3-Acquire and set up Let's Encrypt SSL certificates using Duck DNS for a free hostname and automatic renewal.
4-Configure Apache as a reverse proxy with SSL to securely route traffic to Synapse.
5-Enable federation with Apache on port 8448 and handle necessary port forwarding.

1_InstallAndConfig_Synapse

1-Install required dependencies: lsb-release, wget, apt-transport-https.
2-Download and add Matrix.org GPG key for secure package verification.
3-Add the Matrix.org Debian package repository to the system sources.
4-Update the system package list.
5-Install the matrix-synapse-py3 package.
6-Edit /etc/matrix-synapse/homeserver.yaml to set server name, database credentials, listeners, and logging.
7-Create a server name config override file at /etc/matrix-synapse/conf.d/server_name.yaml.
8-Restart and verify the Synapse service status.
9-Monitor Synapse logs for errors or activity.
10-Set up port forwarding on ports 80, 443, and 8448 for external access and federation.
11-Use network commands and federation tester tools to debug connectivity and federation status.
