# CredAuth

## Description

This app will handle user authentication on behalf of other services.
Technically, it will be:

- An OpenID provider for people wanting to log into other services. - [OpenId](https://github.com/lepture/authlib)
- A mutualTLS certificate provider for client services which would need to authenticate itself to connect to server. - details Undecided

[To automatically apply for web server certs and schedule renewals on publicly trusted ca](https://certbot.eff.org/instructions?ws=other&os=ubuntufocal)
