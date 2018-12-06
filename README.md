# certbot

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-certbot.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-certbot)

Ansible role for certbot

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.certbot`

# Default settings

```
certbot_email: "john_doe@example.com"
certbot_root: /var/www/html
certbot_domains: []
certbot_set_cron: false
certbot_link: false
certbot_regenerate_hour: 0
certbot_regenerate_minute: 0
certbot_regenerate_day_of_month: 1
certbot_ci_build: false
certbot_www_user : www-data
certbot_www_group : www-data

```

# Development

Please check [development guide](DEVELOPMENT.md) for details about developing and testing this role.
