# Helmfile – Required Dependencies & Installation Links
- [Helmfile – Required Dependencies \& Installation Links](#helmfile--required-dependencies--installation-links)
  - [Mandatory Dependencies](#mandatory-dependencies)
    - [1. Helm](#1-helm)
    - [2. Helmfile](#2-helmfile)
    - [3. kubectl](#3-kubectl)
  - [Recommended Dependencies](#recommended-dependencies)
    - [4. helm-diff (Helm plugin)](#4-helm-diff-helm-plugin)

## Mandatory Dependencies

### 1. Helm
- **Version**: Helm v3.12+ (recommended: latest Helm v3)
- **Purpose**: Helmfile uses Helm to install and manage charts.

Installation guide:  
https://helm.sh/docs/intro/install/


### 2. Helmfile
- **Version**: latest stable
- **Purpose**: Declarative tool to manage and deploy Helm charts in one command.

Installation guide:  
https://helmfile.readthedocs.io/en/latest/#installation

Releases (manual install):  
https://github.com/helmfile/helmfile/releases


### 3. kubectl
- **Purpose**: Required to interact with the Kubernetes cluster and validate context.

Installation guide:  
https://kubernetes.io/docs/tasks/tools/


## Recommended Dependencies

### 4. helm-diff (Helm plugin)
- **Purpose**: Used by Helmfile to show diffs before applying changes.

Plugin repository & install instructions:  
https://github.com/databus23/helm-diff

