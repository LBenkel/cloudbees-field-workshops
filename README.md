# <img src="https://mms.businesswire.com/media/20191204005250/en/760213/23/Logo_-_Stacked_-_Full_Color%402x.jpg" width="100" align="top"> CloudBees Field Workshops
These workshop labs demonstrate how to  effectively use CI/CD practices, manage feature flags, and orchestrating releases with CloudBees CI, CloudBees Feature Flags, and CloudBees CD products.

# Workshop Prerequisites

* Internet access to include access to https://github.com and to include the ability to access and use the [GitHub File Editor](https://help.github.com/articles/editing-files-in-your-repository).
* Access to https://app.slack.com
* An account on https://github.com and a basic understanding of how to use GitHub to do things like fork a repository, edit files in the web UI, and create pull requests.
* A basic understanding of Docker: https://docs.docker.com/get-started/
* A basic understanding of Kubernetes: https://kubernetes.io/docs/tutorials/kubernetes-basics/
* A basic understanding of Jenkins Pipelines: https://jenkins.io/doc/book/pipeline/getting-started/
* A basic understanding of feature flags: https://rollout.io/blog/ultimate-feature-flag-guide/
* Finally, we highly recommend using the Google Chrome browser to work through the lab content.

# Workshop Labs & Slides

[Workshop Setup for all workshops](labs/workshop-setup/workshop-setup.md)


## CloudBees CI:

### Slides
https://cloudbees-days.github.io/core-rollout-flow-workshop/core/

### Labs
 * [Lab 1 - CloudBees CI Workshop Setup](labs/core-workshop-setup/workshop-setup.md)
 * [Lab 2 - Configuration as Code (CasC) for CloudBees CI](labs/core-casc/core-casc.md)
 * [Lab 3 - Pipeline Template Catalogs](labs/pipeline-template-catalog/pipeline-template-catalog.md)
 * [Lab 4 - Pipeline Policies](labs/pipeline-policies/pipeline-policies.md)
 * [Lab 5 - Cross Team Collaboration](labs/cross-team-collaboration/cross-team-collaboration.md)
 * [Lab 6 - Hibernating Masters](labs/hibernating-masters/hibernating-masters.md)

>NOTE: If you are returning to the workshop cluster to complete a lab please review this lab on [**Un-hibernating a Master**](labs/hibernating-masters/hibernating-masters.md#un-hibernate-a-master).

## CloudBees Feature Flags:

### Slides
https://cloudbees-days.github.io/core-rollout-flow-workshop/rollout/

If you did not attend the CloudBees CI Workshop or go through the above labs, please follow [these instructions](labs/rolloutPreReqs/rolloutPreReqs.md) before proceeding to Lab 1 below.

### Labs
 * [Lab 1 - CloudBees Feature Flags Workshop Setup](labs/rolloutSetup/rolloutSetup.md)
 * [Lab 2 - Gating Code with CloudBees Feature Flags](labs/rolloutFeature/rolloutFeature.md)
 * [Lab 3 - Controlling the Value of a Feature Flag](labs/rolloutExperiment/rolloutExperiment.md)
 * [Lab 4 - User Targeting](labs/rolloutTargeting/rolloutTargeting.md)
 * [Lab 5 - CloudBees Feature Flags Configuration as Code](labs/rollout-cac/rollout-cac.md)
 * [Lab 6 - CloudBees Feature Flags and Analytics](labs/rolloutAnalytics/rolloutAnalytics.md)




## CloudBees CD:
Coming soon...
 * Lab 1 - Create release pipeline from a service catalog
 * Lab 2 - Add gates to the release pipeline
 * Lab 3 - Merge into master and run through release pipeline
 * Lab 4 - Check out the live app, close the ticket, observe CloudBees CD Dashboard
