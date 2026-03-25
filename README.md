# Dev Container Features

Custom [dev container Features](https://containers.dev/implementors/features/) by **diegosolisfr**, hosted on GitHub Container Registry.

> Fork of [devcontainers/feature-starter](https://github.com/devcontainers/feature-starter)

## Features

### `hello`

A simple greeting feature. Running `hello` inside the built container will print a greeting.

```jsonc
{
    "image": "mcr.microsoft.com/devcontainers/base:ubuntu",
    "features": {
        "ghcr.io/diegosolisfr/devcontainers-features/hello:1": {
            "greeting": "Hello"
        }
    }
}
```

```bash
$ hello
Hello, user.
```

#### Options

| Option | Type | Default | Description |
|--------|------|---------|-------------|
| `greeting` | string | `hey` | Select a pre-made greeting, or enter your own |

## License

See [LICENSE](LICENSE).
