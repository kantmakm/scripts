Docker images with preinstalled [RUST](https://www.rust-lang.org/) i686, [node.js](https://nodejs.org) and [AWS CLI](https://aws.amazon.com/ru/cli/) for [GitLab CI runner](https://gitlab.com/gitlab-org/gitlab-ci-multi-runner).
Usage:
```linux-arm64:
      stage: build
      image: parity/rust-i686:gitlab-ci
      script:
        - cargo build ...
```
