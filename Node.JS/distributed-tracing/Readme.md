This folder contains an example about using OpenTelemetry with Node.JS.

# Commands

- Add tracing dependencies

``` shell
npm install \
@opentelemetry/sdk-node \
@opentelemetry/api \
@opentelemetry/auto-instrumentations-node
```

- Start service

``` shell
# Running app with tracing code loaded
node --require './tracing.js' app.js
```



# Reference

- [Node.JS](https://opentelemetry.io/docs/js/getting_started/nodejs/#example-application)
    > This is an example

- [Data Sources / traces](https://opentelemetry.io/docs/concepts/data-sources/#traces)
