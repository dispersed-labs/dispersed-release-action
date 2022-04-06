# Dispersed Network Release Action

An action for preparing releases to be published on the Dispersed Network.

# Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: dispersed-labs/dispersed-release-action@v1
  with:
    build_dir: build|dist|out|...
    bundle_name: your-project-${{ github.ref_name }}.tgz
    github_token: ${{ secrets.GITHUB_TOKEN }}
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
