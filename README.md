# asdf-openshift-cli

Special thank you to Hazem Hemied [hhemied](https://github.com/hhemied) this is a fork of his project [asdf-openshift-install](https://github.com/hhemied/asdf-openshift-install) with small differences to install `oc`.

![CI](https://github.com/hhemied/asdf-openshift-cli/workflows/CI/badge.svg?branch=main)

[OpenShift-installer CLI](https://github.com/openshift/installer) (oc) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```bash
asdf plugin add openshift-cli https://github.com/mvalin/asdf-openshift-cli.git
```

### List all available versions to install

```basn
asdf list all openshift-cli
```

### Install the latest stable version

```bash
asdf install openshift-cli stable
```

### Install the latest and greatest version

```bash
asdf install openshift-cli latest
```

### Install specific version

```bash
asdf install openshift-cli stable-4.10
```

### Activate a specific version for the current running session

```bash
asdf shell openshift-cli stable-4.10
```

### Activate a specific version for the current shell.

```bash
asdf global openshift-cli stable-4.10
```

## For more details on how to use, please visit [asdf-vm](https://asdf-vm.com/) website

Check the [asdf](https://github.com/asdf-vm/asdf) README for instructions on how to install and manage versions of openshift-cli.
