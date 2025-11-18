# docker-caddy

Custom caddy build that includes github.com/mholt/caddy-ratelimit in order to
apply rate limiting.

The example Caddyfile serves static content and includes an example for how to 
identify clients based on User-Agent that appears to be a valid email address,
and apply a non-default higher rate limit to them if so.
