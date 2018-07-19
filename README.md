# ansible-manage-ssh-user
A small ansible library to manage ssh user

# How to use
- For each group (organization, environment, product, etc..), create its owned inventory. Just follow the sample directory on inventories. 'sample' is presentated for a group of server.

- In order to add a new user, create a new user on the hosts.yml, look like the hosts.yml sample
- In order to remove a old user, change the state is absent.
