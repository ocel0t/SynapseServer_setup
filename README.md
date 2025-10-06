0_PrepareMachine

Synapse Matrix homeserver setup on a Debian VM with these key steps:

1-Prepare the Debian system with a new user, upgrades, and enables SSH.
2-Install and configures PostgreSQL database for Synapse.
3-Acquire and set up Let's Encrypt SSL certificates using Duck DNS for a free hostname and automatic renewal.
4-Configure Apache as a reverse proxy with SSL to securely route traffic to Synapse.
5-Enable federation with Apache on port 8448 and handle necessary port forwarding.
