# nginx-shibboleth
nginx with shibboleth modules added, contained in a docker image. It is based off of the official [nginx](https://hub.docker.com/_/nginx/) docker image, which is debian based.

The built modules are:

* [nginx-http-shibboleth](https://github.com/nginx-shib/nginx-http-shibboleth)
* [headers-more-nginx-module](https://github.com/openresty/headers-more-nginx-module)

This docker image was built using [instructions](https://github.com/ConsortiumGARR/idem-tutorials/blob/master/idem-community/HOWTO-Shibboleth/Service-Provider/Debian/HOW%20TO%20SETUP%20A%20SHIBBOLETH%20SP%20WITH%20NGINX.md) to add shibboleth integration with nginx, and making use of the [pkg-oss](https://www.nginx.com/blog/creating-installable-packages-dynamic-modules/) utility to create dynamic modules.


