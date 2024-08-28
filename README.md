# 📦 Bigbluebutton on Kubernetes automatic scale

This is using Bigbluebutton Docker Version: 2.3.0 | [Bigbluebutton Docker](https://github.com/bigbluebutton/docker/)

- Build your own dockers on /mod
- search for "destinyakpo" and update to your docker image
- search for srv02.bbb.t-assets.de and update to your domain
- search for \<\<update this\>\> and update your value. 
- run ./deploy.sh
  
Each scaled bbb instance will have the domain ${HOSTNAME}.srv02.bbb.t-assets.de so make scripts to update record set of domain to it.

## Key Features
  - Remove completely any dependency on instance or private or Public IP.
  - Automatically scale on high load
  
## Note
  - You should manage your sub domains and distribute your room to them (easy task)
  - All firewall on docker host for Bigbluebutton need to be exposed. Check bbb firewall docs.

Tested on Digitalocean
  
  
