<p align="center">
  <a href="https://github.com/a-skua/trunk-action/actions"><img alt="trunk-action status" src="https://github.com/a-skua/trunk-action/workflows/build-test/badge.svg"></a>
</p>

# `trunk-action`

Install [`Trunk`](https://github.com/trunk-rs/trunk) by downloading the
executable (much faster than `cargo install trunk`, seconds vs minutes).

## Usage

```yaml
- uses: a-skua/trunk-action@0.5.1
  with:
    # Optional version of trunk to install(eg. 'v0.19.1', 'latest')
    version: 'latest'
```

## Resources

- Forked https://github.com/jetli/trunk-action
- https://github.com/trunk-rs/trunk
