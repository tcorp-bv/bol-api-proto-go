# Bol-api-proto-go
Protobuf bindings for the bol.com v3 retailer api types.

## Getting started

```golang
import (
	api "github.com/tcorp-bv/bol-api-proto-go/bol-api-proto-go"
)

```
In your `go.mod` you can add (or let this be generated):
```golang
require (
  github.com/tcorp-bv/bol-api-proto-go v1.0.0
)
```

## Motivation
Internally, we terminate the bol.com retailer api and store a lot of its resources in an intermediary database. This allows internal services to not worry about any of the rate limits/authentication stuff.
