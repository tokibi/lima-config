# lima-config

## Installation

```bash
$ brew install lima
```

## Create VM

```bash
$ limactl start default.yaml
```

## Setup macOS environments

```bash
$ echo 'export DOCKER_HOST=tcp://127.0.0.1:2375' >> ~/.zshrc
```

## Cleanup

```bash
$ limactl stop && limactl delete default
```
