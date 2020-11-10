![sWAF Logo](https://github.com/swaf-project/swaf-docker/raw/master/logo/skull_mask_266.png)

**sWAF** is a **simple Web Application Firewall** [docker image](https://hub.docker.com/r/swafproject/swaf), pre-packaged to be easily used within your web services architecture.

It runs [NGINX](https://www.nginx.com/) as a dedicated reverse proxy embedding powerful WAF engines: [ModSecurity 3](https://www.modsecurity.org/), using [OWASP® ModSecurity Core Rule Set (CRS)](https://coreruleset.org/) rules, and [NAXSI](https://github.com/nbs-system/naxsi). It uses [acme.sh](https://acme.sh/) for Let's Encrypt and others free CA support.

## Getting Started

1. Get sWAF docker image:

    ```shell
    docker pull swafproject/swaf
    ```

2. Start a sWAF container:

    ```shell
    docker run -d --name swaf --restart always --net host swafproject/swaf
    ```

## Further Details

* All details on <https://github.com/swaf-project/swaf-docker>

* Full documentation on the [Wiki](https://github.com/swaf-project/swaf-docker/wiki)

### And obviously...

...in case of any issue: [https://github.com/swaf-project/swaf-docker/issues](https://github.com/swaf-project/swaf-docker/issues)

---
© The sWAF Project Team - [WebSite](https://swaf-project.github.io) / [GitHub](https://github.com/swaf-project/swaf-docker) / [Wiki](https://github.com/swaf-project/swaf-docker/wiki)
