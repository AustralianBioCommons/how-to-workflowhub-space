---
title: Create a new registry entry for a workflow
type: Guide
sidebar: false
---


## Quick start guide

1. [Register or Log-in to WorkflowHub](#1-are-you-a-new-workflowhub-user)
2. [Join a team, or create a new Team](#2-join-a-team-or-create-a-new-team)
3. [Register your workflow](#3-registering-the-workflow)
4. [Add minimum metadata](#4-add-minimum-metadata)
5. [Add attributions for other workflows](#5-add-attributions-for-other-workflows)
6. [Create a DOI](#6-create-a-doi)
7. [Add workflow How-to Guide metadata](#7-add-workflow-how-to-guide-metadata)
8. Done. Thank you for contributing!

{% include callout.html type="tip" content="[See WorkflowHub documentation for more information](https://about.workflowhub.eu/docs/registering_workflows/)." %}


### Example

An example workflow that follows the guidelines described:
> Price, G., & Farquharson, K. (2022). PacBio HiFi genome assembly using hifiasm v2.1. WorkflowHub. [https://doi.org/10.48546/WORKFLOWHUB.WORKFLOW.221.3](https://doi.org/10.48546/WORKFLOWHUB.WORKFLOW.221.3)

![](images/example.png)


## More in-depth guide

### 1. Are you a new WorkflowHub user?

- **Yes:** [Register with WorkflowHub](https://workflowhub.eu/signup). Make sure to add your organisation(s) / affiliation(s).
- **No:** [Login to WorkflowHub](https://workflowhub.eu/login)


### 2. Join a team, or create a new Team

Is there a Team available to join? Below are the current options in the BioCommons space. If any of these Teams are suitable, click the link below to request membership:

- {% tool "galaxy-team" %} - [`Request to join`](https://workflowhub.eu/projects/54/guided_join)
- {% tool "sih-team" %} - [`Request to join`](https://workflowhub.eu/projects/43/guided_join)
- {% tool "pawsey-team" %} - [`Request to join`](https://workflowhub.eu/projects/42/guided_join)
- {% tool "qcif-team" %} - [`Request to join`](https://workflowhub.eu/projects/41/guided_join)
- {% tool "janis-team" %} - [`Request to join`](https://workflowhub.eu/projects/48/guided_join)
- {% tool "nci-team" %} - [`Request to join`](https://workflowhub.eu/projects/289/guided_join)

If there is no suitable Team, you can [request a new one in the `Independent Teams` Space](https://workflowhub.eu/projects/guided_create).

Instructions for requesting a Team in the `Australian BioCommons` Space will be available soon.


### 3. Registering the workflow

Follow the instructions available in the WorkflowHub documentation to:

1. [**Import a Git repository**](https://about.workflowhub.eu/docs/registering_workflows/adding-files/#git), and
2. [**Complete workflow metadata**](https://about.workflowhub.eu/docs/registering_workflows/complete-workflow-metadata/)


### 4. Add minimum metadata

The minimum metadata expected for a workflow includes:

| Field                      | Description|
|----------------------------|--------------------------------------------------------------------|
| Workflow title             | Make sure the title is descriptive and highlights what the workflow does.|
| Creator(s)               | If you have included a `CITATION.cff` file in your GitHub repository, WorkflowHub can parse this and automatically populate the creator field. |
| Description              | Note that descriptions included in GitHub repository README files will be automatically parsed by WorkflowHub. |
| Maturity                 | Indicate if the workflow is `mature` or a `work-in-progress`. |
| License                    | Note that if a license file is included in your GitHub repository it will be automatically parsed by WorkflowHub. |
| EDAM Topics and Operations | Add concepts from [EDAM](https://github.com/edamontology/edamontology) as standardised short descriptions of workflow domain, purpose, and function. You can search for EDAM terms within the WorkflowHub workflow registration wizard. You can also use [EDAM browser](https://edamontology.github.io/edam-browser/) to explore and search the EDAM ontology for appropriate concepts. |


### 5. Add attributions for other workflows

If the workflow you are registering is based on another workflow that is also registered in WorkflowHub, you can add this workflow to the `Attribution` metadata field during registration (see below).

![](images/attributions.png)


### 6. Create a DOI

You can mint a [digital object identifier (DOI)](https://www.doi.org/) for your workflow using WorkflowHub. This allows you to create a *persistent* link to specific versions of your workflow and to also generate a citation for your workflow.

Follow the instructions available in the WorkflowHub documentation to [**mint a DOI**](https://about.workflowhub.eu/docs/citable/).


### 7. Add workflow How-to Guide metadata

### 8. Done, Thank you for contributing!

