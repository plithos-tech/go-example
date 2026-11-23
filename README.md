# go-example

A minimal Go HTTP server that responds with `Hello, World!`.

## Run

Requires Go 1.26 or later.

```sh
go run .
```

Open http://localhost:8080.

Set `HOST` and `PORT` to change the listen address. Empty or unset values default
to `localhost` and `8080` respectively.

```sh
HOST=0.0.0.0 PORT=3000 go run .
```
