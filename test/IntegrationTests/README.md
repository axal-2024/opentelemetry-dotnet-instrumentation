# Integration Tests

## OTLP protos

Some integration tests will validate the data communicated over OTLP.
The protos for OTLP can be found in the
[opentelemetry](./opentelemetry) directory. These protos are copied from the
[opentelemetry-proto repository](https://github.com/axal-2024/opentelemetry-proto).
When updating the protos to a new version you just need to copy the
`opentelemetry` directory between the two projects.
