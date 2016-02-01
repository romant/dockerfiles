# [ placeholder for Orchard's wisdom / intro ]

## Building

### Get it

clone this repo, and then:

`git submodule update --init --recursive` to make sure you obtain the Swagger-UI code-base

### Build it

Replace `[fapi]` with your choice of a 

`docker build -t fapi .`

## Run it

`docker run --rm -p 80:8080 fapi`