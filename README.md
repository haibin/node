# node

```
> kitchen init --create-gemfile
> bundle install
> kitchen create
> knife bootstrap --sudo --ssh-user vagrant --ssh-password \
vagrant --no-host-key-verify node-centos65.vagrantup.com -N node
```