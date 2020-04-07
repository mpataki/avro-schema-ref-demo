# avro-schema-ref-demo

This repo is intended to demonstrate an avro schema reference ordering described in this [issue](https://github.com/zolyfarkas/spf4j/issues/42)

Depending on your operating system, running `mvn compile` may or may not work. While on my operating system this repo as is works fine, if I rename `src/main/resource/01_B.avsc` to `02_B.avsc`, for example, the plugin will compile the schemas in an order which causes the issue descibed in the link above.
