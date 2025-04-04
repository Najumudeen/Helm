### What helm offers?
```
Agility
Simplicity
Consistency
```
### Agility

Helm Integrates into GitOps and CICD
Simple Deployment and upgrades through helm
Helm Automates manual tasks
Risk of error reduced during deployment

Unlocked via Troubleshooting technique

Increased resilience of apps
Focus on testing and validation
Early spotting of issues.
Better Maintaining control
Reliability of cloud-native application.

### Helm

The kubernetes package manager
Manages packages(charts) of kubernetes resources. Website click [here](https://helm.sh)

## Artifact registry? click [here](https://artifacthub.io)

Upload helm chart

Helm helps you manage kubernetes applications

```
Manage Complexity
Easy Updates
Simple Sharing
Rollbacks
```

### Why are we using HELM?

Reason to use Helm?

We want to manage complex kubernetes applications


### Alternative to Helm

|Category                     |       Helm                                     |       Kustomize                                |
|  :------------              |  :--------------                               |  :------------                                 |
| Method of operation         | Templating                                     |  Overlays                                      |
| Ease Of Use                 | More Complex due to templating                 |  Simpler, as if works with raw YAML            |
| Package Support             | Yes, Packages applications as charts           |  No, but allows for customization of manifests |
| Integration with kubernetes | Requires a separate CLI                        |  Integrates natively with kubectl              |
| Configuration Apporach      | Imperative, with a focus on package manaagement|  Declarative, with focusing on customization   |

> [!Note]
> helm-cli

### Installing helm
```
curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash
```

### Creating a HELM chart
```
helm create webserver
```

### install tree command
```
brew install tree
```

### Helm Chart

The Kubernetes package
The Kubernetes manifests bundled ready to be installed by a single command
Dependencies, Values and Templates

A Chart a Helm package, it contains all of the resources defintions necessary to run an application, tool or service inside of a kubenetes cluster.
A Repository is the place where charts can be collected and shared. it's like Perl's 
A Release is an instance of a chart running in a kubernetes cluster. Consider a MYSQL chart. if you want two databases running in your cluster. you can install that chart twice. Each one will have its own release.

https://artifacthub.io

    




