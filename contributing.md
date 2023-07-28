# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test protoc-gen-connect-go https://github.com/dylanrayboss/asdf-protoc-gen-connect-go.git "protoc-gen-connect-go --version"
```

Tests are automatically run in GitHub Actions on push and PR.
