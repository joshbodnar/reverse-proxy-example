# Setup Instructions

For this example to work out of the box, add the hosts to your `/etc/hosts` file:

```
127.0.0.1 a.localhost
127.0.0.1 b.localhost
127.0.0.1 c.localhost
```



## Run The Stack

```
docker-compose up -d
```

then visit any of the following: 

- [http://a.localhost](http://a.localhost)

- [http://b.localhost](http://b.localhost)

- [http://c.localhost](http://c.localhost)

  

## Using a Different Hostnames

If you wish to use a different hostname & sub-domain, edit `./proxy/nginx.conf` as needed to reflect the correct host name under the `server_name` property of each server. Then modify your `/etc/hosts` file or DNS to reflect the same changes.

