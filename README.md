# Schleifner/github-coredump

Unpload coredump from ubuntu and unload build_dir optionally

## Limit

Only support ubuntu, and both enabled apport service.

## Usage

```yaml
- uses: Schleifner/github-coredump@v1
  with:
    # Optional artifact name.
    name: 
    # Optional path. upload together with coredump path
    build_dir:
```
