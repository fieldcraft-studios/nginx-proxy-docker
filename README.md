# nginx-proxy Docker

Docker file for nginx-proxy and [Lets Encrypt](https://letsencrypt.org). This allows subdomains to be re-routed to correct port on NAS box eg `https://media.fieldcraftstudios.com` rather than `http://media.fieldcraftstudios.com:2020`.

Blog post instructions for setting up nginx reverse proxy:  
<https://medium.com/@francoisromain/host-multiple-websites-with-https-inside-docker-containers-on-a-single-server-18467484ab95>

Please note, new `.env` file, with location of nginx-proxy on the server.

All `.env` files stored on Slack.
