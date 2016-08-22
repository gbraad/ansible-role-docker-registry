Docker Registry
===============


Requirements
------------


Role Variables
--------------


Dependencies
------------

At the moment the installation of `docker-python` has not been added.
If the script fails, please perform the installation with:

```
$ yum install -y docker-python
```


Example Playbook
----------------

```
- name: Deploy docker registry
  hosts: localhost
  roles:
    - gbraad.docker-registry
```


License
-------


Author Information
------------------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad) |
