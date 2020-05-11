# Ansible - MariaDB Deployment

An Ansible playbook for deploying MariaDB on CentOS/Redhat. The playbook specifically covers:
- Installation of MariaDB 10.2 from official repositories
- Setting up the root password
- Ensuring idempotency
- Creation of a user and a database for Wordpress

## Requirements
No specific requirements

## Variables
`{{ mysql_root_password }}` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `Variable for setting up root password`

`{{ wp_user_pass }}` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `Variable for setting up DB user password`


## Contributing
Pull requests are welcome.
