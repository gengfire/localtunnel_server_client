# localtunnel_server_client
## base on localtunnel-server

base on [localtunnel_server_client](https://travis-ci.org/localtunnel/server)

change: bacause of firewalls, add argvs on server, custom TCP socket port.

## overview ##

#### setup

```shell
# pick a place where the files will live
git clone git://github.com/gengfire/localtunnel_server_client.git
cd localtunnel_server_client/server
npm install

# server set to run on port 1234 and TCP socket port 2001
bin/server --port 1234 --socket-port 2001
```
