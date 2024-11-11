# ue-css-cppgraphqlgen

The [cppgraphqlgen](https://github.com/microsoft/cppgraphqlgen) C++ library packaged for use in Satisfactory modding.

See [.artifact/usage.md](.artifact/usage.md) for usage information.

## Notes

The version of cppgraphqlgen in the lib folder was build with `GRAPHQL_BUILD_CLIENTGEN` and
`GRAPHQL_BUILD_SCHEMAGEN` disabled so that the cppgraphqpgen will not be linked against boost,
cutting down on the artifact size. Static copies of the clientgen and schemagen binaries
created from a separate build are included in the tools directory.

## License

The licenses of cppgraphqlgen (MIT), rapidjson (MIT), and boost (Boost License)
are included in the `share/**/copyright` files located within the release artifact.
