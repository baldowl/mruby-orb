# mruby-orb [![CircleCI status](https://circleci.com/gh/baldowl/mruby-orb.svg "CircleCI status")](https://circleci.com/gh/baldowl/mruby-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/baldowl/mruby)](https://circleci.com/orbs/registry/orb/baldowl/mruby) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/baldowl/mruby-orb/master/LICENSE)

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
          version: 2.0.1

      - mruby/test:
          version: master
```

## License

This code is released under the MIT License: see LICENSE file.
