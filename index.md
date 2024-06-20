---
title: How-to contribute a workflow to the BioCommons WorkflowHub space
sidebar: false
---


{% include callout.html type="tip" content="Are you looking to register a new version of an existing workflow, or edit the metadata for an existing workflow? [See this page instead](workflow_maintenance)!" %}


## Quick start guide

1. [Create a workflow!](#create-a-workflow) 
2. [Improve the workflow (i.e. version control, license, documentation)](#improve-the-workflow)
3. [Register or Log-in to WorkflowHub](#are-you-a-new-workflowhub-user)
4. [Join a team, or create a new Team](#join-a-team-or-create-a-new-team)
5. [Register your workflow](#register-your-workflow)
6. [Add minimum metadata](#add-minimum-metadata)
7. [Create a DOI](#create-a-doi)
8. Done. Thank you for contributing!


## Example

An example workflow that follows the guidelines described:
> Price, G., & Farquharson, K. (2022). PacBio HiFi genome assembly using hifiasm v2.1. WorkflowHub. https://doi.org/10.48546/WORKFLOWHUB.WORKFLOW.221.3


## Things to note

- All workflows in the Australian BioCommons WorkflowHub space will automatically appear in the [WorkflowFinder service](https://australianbiocommons.github.io/2_1_workflows.html) as well.
- A minimum set of metadata is expected for workflows registered in the BioCommons WorkflowHub space. These are described in more detail in the [register your workflow section](#register-your-workflow).


## More in-depth guide

### 1. Create a workflow

{% include callout.html type="note" content="Did you create your workflow in Galaxy? If so, don't forget to share it on the Galaxy instance where you created the workflow! e.g. https://usegalaxy.org.au/workflows/list_published" %}

### 2. Improve the workflow

{% include callout.html type="note" content="Completing all the steps in part #1 before visiting WorkflowHub will ensure a user can find, understand, and reuse your workflow. Even more importantly, it will save you time later!" %}


**2.1 Version control the workflow with git:** Add your workflow to a git repository (e.g. GitHub). This allows easy import into WorkflowHub (and in particular the import of new versions!).

**2.2 License the workflow for reuse:** Make sure to add a license that allows others to reuse your workflow. If you are unsure which open source license to pick, the standard for the Australian BioCommons is [Apache 2.0](https://spdx.org/licenses/Apache-2.0.html).

**2.3 Document the workflow well:** Update documentation so new users can understand what the workflow does, how it does this, and why. There are multiple options for how to document a workflow and include this in WorkflowHub. See the [documentation appendix](#documentation) for more information.

**2.4 Add standard files (optional but recommended):** Consider adding a machine-readable standard file format to your GitHub repository (or similar). There are wizards for creating these files, so you don't need to know how to build them yourself.

- **codemeta.json** --- [wizard link](https://codemeta.github.io/codemeta-generator/) 
- **CITATION.CFF** --- [wizard link](https://citation-file-format.github.io/cff-initializer-javascript/#/)


**2.5 [Create a workflow release](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases)** 


**2.6 Now that the hard part is completed, proceed to WorkflowHub!**


### 3. Are you a new WorkflowHub user?

- **Yes:** [Register with WorkflowHub](). Make sure to add your organisation(s) / affiliation(s).
- **No:** [Login to WorkflowHub]()


### 4. Join a team, or create a new Team

Is there a Team available to join? Below are the current options in the BioCommons space. If any of these Teams are suitable, click the link below to request membership:

- [**Galaxy Australia**](https://workflowhub.eu/projects/54) - [request to join](https://workflowhub.eu/projects/54/guided_join)
- [**Sydney Informatics Hub**](https://workflowhub.eu/projects/43) - [request to join](https://workflowhub.eu/projects/43/guided_join)
- [**Pawsey Supercomputing Centre**](https://workflowhub.eu/projects/42) - [request to join](https://workflowhub.eu/projects/42/guided_join)
- [**QCIF**](https://workflowhub.eu/projects/41) - [request to join](https://workflowhub.eu/projects/41/guided_join)
- [**Janis**](https://workflowhub.eu/projects/48) - [request to join](https://workflowhub.eu/projects/48/guided_join)

If there is no suitable Team, you can create a new one by [**clicking this link**](https://workflowhub.eu/projects/guided_create). Make sure you select the `Australian BioCommons` Space.


### 5. Registering the workflow

Follow the instructions available in the WorkflowHub documentation to:

1. [**Import a Git repository**](https://about.workflowhub.eu/docs/adding-files/#git), and
2. [**Complete workflow metadata**](https://about.workflowhub.eu/docs/complete-workflow-metadata/)


### 6. Add minimum metadata

The minimum metadata expected for a workflow includes:

**Workflow title**: Make sure the title is descriptive and highlights what the workflow does.

**Creator(s)**: If you have included a `CITATION.cff` file in your GitHub repository, WorkflowHub can parse this and automatically populate the creator field.

**Description:** Note that descriptions included in GitHub repository README files will be automatically parsed by WorkflowHub.

**Maturity:** Indicate if the workflow is `mature` or a `work-in-progress`.

**License:** Note that if a license file is included in your GitHub repository it will be automatically parsed by WorkflowHub.

**EDAM Topic(s) and Operation(s):** Add concepts from [EDAM](https://github.com/edamontology/edamontology) as standardised short descriptions of workflow domain, purpose, and function. You can search for EDAM terms within the WorkflowHub workflow registration wizard. You can also use [EDAM browser](https://edamontology.github.io/edam-browser/) to explore and search the EDAM ontology for appropriate concepts.


### 7. Create a DOI

You can mint a [digital object identifier (DOI)](https://www.doi.org/) for your workflow using WorkflowHub. This allows you to create a *persistent* link to specific versions of your workflow and to also generate a citation for your workflow.

Follow the instructions available in the WorkflowHub documentation to [**mint a DOI**](https://about.workflowhub.eu/docs/citable/).


### 8. Done, Thank you for contributing!


## Appendix

### Documentation

#### Option 1: add documentation to your GitHub repository

(use a template to make this easier)


#### Option 2: create a How-to Guide

(use a template to make this easier)


#### Option 3: create documentation and upload to WorkflowHub as a document or SOP

#### Option 4: add a description directly to the WorkflowHub entry


