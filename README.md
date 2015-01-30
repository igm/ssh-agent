# ssh-agent
Provides SSH access into PWS/CF container

Usage:
```sh
$ git clone https://github.com/igm/ssh-agent
$ cd ssh-agent
$ cf push
$ cf app ssh-agent        # to see the url the app is bound to
$ go get github.com/igm/ssh-buildpack/src/client
$ client APP_URL          # go get should produce binary 
$ ssh foo@localhost -p 2222
foo@localhost\'s password: # enter "bar" as password
```
