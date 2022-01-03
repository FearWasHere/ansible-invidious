### Prerequisites
* ansible
* a desire to install invidious
* an instance on which to install it

### To install
just run the playbook.  what am i, your mother?

ok, fine.  it expects the following extra variables to be passed:
* target (the host you'll install on)
* remote_user (the login ansible will use on the remote host)
* pg_user (the postgres user to create)
* pg_pass (the postgres password)