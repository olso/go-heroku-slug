# go-heroku-slug

This is heroku `go` compiler microservice for WebAssembly Studio. It is also a slug builder.

Mostly copied from [rust-heroku-slug](https://github.com/yurydelendik/rust-heroku-slug)

## Running service locally

## Change configuration in WebAssembly Studio

The `go` endpoint address can be located at the [config](https://github.com/wasdk/WebAssemblyStudio/blob/master/config.json) and be changed locally.

## Building and installing the slug

Run APP=<your-heroku-app> make publish to fully build and setup slug at your app.
