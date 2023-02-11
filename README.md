# `ansible-role-nextcloud`: install and update [nextCloud](https://nextcloud.com/fr/) server

This [Ansible](https://www.ansible.com) role aims at installing the [nextCloud](https://nextcloud.com/fr/) application on Fedora.

## Role variables

There is no default value.

#### Software
- `nextcloud_release_url`: url to the version of nextcloud to install (`.zip` file)
- `nextcloud_release_sha256_sum`: sha256 sum of this file

#### Domain
- `nextcloud_domain`: domain under which the application will be known

#### Admin user
- `nextcloud_admin_user`: user with administration rights on the instance
- `nextcloud_admin_password`: admin user password

#### Database
- `nextcloud_db`: name of the database to create
- `nextcloud_db_user`: name of the user with privileges over `nextcloud_db`
- `nextcloud_db_password`: database user password