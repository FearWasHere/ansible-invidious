### What this does
this will install <a href=https://github.com/iv-org/invidious>invidious</a> and its dependencies, as well as setting up an nginx reverse proxy, so you can be lazy like me and not have to remember that it runs on port 3000.  sure, NOW i remember that.

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
