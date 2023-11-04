# javascript-web-htmx-get-mustache-java-spring-api-dolt-simple

## Description
A demo of htmx using a java springboot
api to return contents of table from
dolt.

## Tech stack
- htmx
    - get
    - ext
    - swap
    - target
- mustache
- java
    - spring
    - cors
- dolt

## Docker stack
- httpd:latest
- maven:3-openjdk-17
- dolthub/dolt-sql-server

## To run
`sudo ./install.sh -u`
- Available at http://localhost

## To stop
`sudo ./install.sh -d`

## To see help
`sudo ./install.sh -h`

## Credit
- [Htmx clientside template](https://htmx.org/extensions/client-side-templates/)
- [Htmx rendering JSON](https://marcus-obst.de/blog/htmx-json-handling)