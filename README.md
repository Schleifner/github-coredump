# Schleifner/github-coredump

Upload coredump from ubuntu and unload build_dir optionally

## Limit

Only support ubuntu that has apt package manager.

## Usage

```yaml
- uses: Schleifner/github-coredump@v1
  with:
    # Optional artifact name.
    name: 
    # Optional path. upload together with coredump path
    build_dir:
```
