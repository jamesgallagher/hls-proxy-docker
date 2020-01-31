# hls-proxy-docker
Docker to setup HLS Proxy

This is a very simple docker, it doesn't do anything more than download HLS Proxy and run it.

## Installation

First `git clone` this repository, create a `local.json` file in the `data` directory to add your HLS sources and EPG data. 
`cd` to the repo directory and run
```bash
docker-compose up --build -d
```

The proxy will be available on http://localhost:3080 or http://YOUR_WEB_SERVER:3080

More information at https://www.hls-proxy.com
