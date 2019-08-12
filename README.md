# nginx-proxy Docker

Docker file for nginx-proxy and [Lets Encrypt](https://letsencrypt.org). This allows subdomains to be re-routed to correct port on NAS box eg `https://media.fieldcraftstudios.com` rather than `http://media.fieldcraftstudios.com:2020`.

* Blog post instructions for setting up nginx reverse proxy:  
<https://medium.com/@francoisromain/host-multiple-websites-with-https-inside-docker-containers-on-a-single-server-18467484ab95>
* [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy) automates the creation of nginx configs and reloads the proxy server when a container starts and stops.
* nginx-proxy has a [LetsEncrypt companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion), which allows the automatic creation and renewal of HTTPS certificates.
* Please note, new `.env` file, with location of nginx-proxy on the server.
* All `.env` files stored on Slack.
