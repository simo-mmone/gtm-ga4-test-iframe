# GTM with GA events inside an iframe

This repo is a test environment aimed to allow the message passing of gtm events trough an iframe

## Local Development

1) start booking-frontend's docker
2) start php server (or similar) `php -S localhost:8080`
3) start ngrok to expose it to the web `ngrok http 8080`
4) visit the url and add `?local=yes` to the url