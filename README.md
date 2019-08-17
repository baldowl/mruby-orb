# mruby-orb

An experiment/toy.

## Examples

```yaml
version: 2.1

orbs:
  mruby: baldowl/mruby@XXX

workflows:
  version: 2

  test:
    jobs:
      - mruby/test:
          version: "2.0.1"

      - mruby/test:
          version: "master"
```

## License

This code is released under the MIT License: see LICENSE file.
