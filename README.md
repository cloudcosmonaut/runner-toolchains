# Runner toolchains

Workflows to automatically create toolchains for installing in the runners to cache the tool (e.g. node, go, etc.)

You can install these cached toolchains in the `RUNNER_DIR/_work/_tool` folder grouped by tool. Just extract the toolchain to the `RUNNER_DIR/_work/_tool` folder and it will be automatically installed. e.g. `tar -xzf node_tool_cache.tar.gz -C RUNNER_DIR/_work/_tool/node`

* [DotNet](.github/workflows/update-dotnet.yaml)
* [Go](.github/workflows/update-go.yaml)
* [Java](.github/workflows/update-java.yaml)
* [Node](.github/workflows/update-node.yaml)
* [Python](.github/workflows/update-python.yaml)
