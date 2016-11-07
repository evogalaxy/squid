# squid

Install Squid.

## Tasks

Everything is in the `tasks/main.yml` file.

## Available variables

* `squid_address` : IP address for internal/outgoing traffic (default: Ansible detected IPv4 address) ;
* `general_alert_email`: email address to send various alert messages (default: `root@localhost`).
* `log2mail_alert_email`: email address to send Log2mail messages to (default: `general_alert_email`).

The full list of variables (with default values) can be found in `defaults/main.yml`.