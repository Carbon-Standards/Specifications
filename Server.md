# Carbon Server

## Metadata

Metadata can be fetched from a Carbon server by making a `GET /` request.

[`CarbonMeta`](https://github.com/Carbon-Standards/Types/blob/main/index.d.ts#L5) defines how a certain Carbon server will behave. Client implementations should read this data before opening a connection to the server.

`CarbonMeta.versions` define what version(s) of the specification are supported by the server. `CarbonMeta.maintainer` can optionaly be set by the maintainer if they like. `CarbonMeta.project` is defined by the implementation of the Carbon server.

Other feilds of this meta data will be described in detail within other sections of the specifications.

## Versions

All versions routes are defined with this pattern `/v${version}/`.

- [v1](./v1.md)
