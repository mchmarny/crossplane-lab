# WIP: crossplane-lab

Collection of [crossplane](https://crossplane.io) labs.

## Prerequisites 

* kind (`brew install kind`)
* kubectl `brew install kubectl`)
* helm (`brew install helm`)
* crossplane CLI (`curl -sL https://raw.githubusercontent.com/crossplane/crossplane/master/install.sh | sh`)

## Setup

This will create a local `kind` cluster named (`kind-xp`) and configure it with minimal GCP configuration (service account: `crossplane-sa`)

```shell
./setup
```


## Disclaimer

This is my personal project and it does not represent my employer. While I do my best to ensure that everything works, I take no responsibility for issues caused by this code.