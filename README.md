# python-web-api-flask-traefik-postgres-simple

## Description
Creates an api of `dog` for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.
Uses self-signed ssl.

## Tech stack
- python
- flask
- postgres
- reverse proxy
- ssl

## Docker stack
- alpine:edge
- python:latest
- postgresql
- traefik:v2.4

## To run
`sudo ./install.sh -u`
- Endpoint
  - [Availble](https://myapi.docker.localhost/dog)
  
## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
