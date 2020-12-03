# Ansible Role: jameseck.google_chrome

A simple role to install google-chrome on Fedora.

## Role Variables

Available variables are listed below along with default values (`defaults/main.yml`):

    google_chrome_package_name: google-chrome-stable
  The name of the google chrome package to install (google-chrome-stable, google-chrome-unstable, etc).

## Example Playbook

    - hosts: workstation
      roles:
        - jameseck.google_chrome

## License

MIT / BSD

## Author Information

James Eckersall
