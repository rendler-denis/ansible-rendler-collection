Role ssh-keys
=========

This role deploys the ssh keys to a specific user.


Role Variables
--------------
ssh_keys.deploy - an array of user and keys to deploy

ssh_keys:
  deploy:
    - user: root
      sshkey: ssh-rsa AAAA....
      comment: 141


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ssh-keys


Author Information
------------------

Name: Denis Rendler
WEb: www.denis.rendler.me