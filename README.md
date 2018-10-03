# CSV-Exporter


## Goals

* Read a JSON request and display list of states at alphabetical order and also display number of clients of each state

## Requirements

### Install Docker engine and docker-compose

docker-compose up --build

## Request APP 

Request application

`# curl -XPOST -H "Authorization: Token $token " http://$hostname:9900/api -H "Content-Type: application/json" -d  `

Example Command to request:

`# curl -H "Authorization: Token Tr8DN93e6MFCrH8fO0BASrRtbTTjDJ5X" http://172.16.27.115:9900/api -H "Content-Type: application/json" -d "@customer.json"`

Example Output

```
[
  [
    "SC",
    2
  ]
]
```
