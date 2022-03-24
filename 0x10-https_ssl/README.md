File: 0-world_wide_web Configures your domain zone so that the subdomain www points to your load-balancer IP (lb-01).

File: 1-haproxy_ssl_termination Creates a certificate using certbot and configure HAproxy to accept encrypted traffic for your subdomain www..

File: 100-redirect_http_to_https Configures HAproxy to automatically redirect HTTP traffic to HTTPS.