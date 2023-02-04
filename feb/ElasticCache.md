# AWS Elastic Cache - Redis

- Client API SDK is equally important as Elastic Cache Setup.
- You cannot have infinite connections to Redis.
- Understand How EventLoop work before trying to apply any changes to cluster.
- Redis is quite fast, if not your setup is wrong.
- Always try to write and read from byte/hash data to redis.
- Infinite scaling is myth.

## Recommendations
- Use [Twemproxy](https://github.com/twitter/twemproxy) - if you not want to manage the connections to Redis clusters
- Always try to write and read from byte/hash data to redis.
- Redis is not varnish or CDN
