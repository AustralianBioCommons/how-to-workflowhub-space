---
title: Align to workflow standards
type: Guide
sidebar: false
---

Completing the steps below before visiting WorkflowHub will ensure a user can find, understand, and reuse your workflow. Importantly, it will also save you time later!


### 1. Create a workflow

{% include callout.html type="note" content="Did you create your workflow in Galaxy? If so, don't forget to share it on the Galaxy instance where you created the workflow! e.g. [https://usegalaxy.org.au/workflows/list_published](https://usegalaxy.org.au/workflows/list_published)" %}


### 2. If you haven't already, then version control the workflow with git

Add your workflow to a Git enabled repository (e.g. [GitHub](https://github.com/)). This allows easy import into WorkflowHub, and in particular the import of new workflow versions!


### 3. License the workflow for reuse

Make sure to add a license that allows others to reuse your workflow. This resource can help you choose a license: https://choosealicense.com/

If you are still unsure which open source license to pick, the standard for the Australian BioCommons is [Apache 2.0](https://spdx.org/licenses/Apache-2.0.html).


### 4. Document the workflow well

Update documentation so new users can understand what the workflow does, how it does this, and why. There are multiple options for how to document a workflow and include this in WorkflowHub: 

- {% tool "repository" %}
- {% tool "guide" %}
- {% tool "sop" %}
- {% tool "wfh-entry" %}.


### 5. Add a standard metadata file

Consider adding a machine-readable standard file format like `CITATION.cff` or `codemeta.json` to your  workflow repository (e.g. GitHub, or similar). There are wizards for creating these files, so you don't need to know how to build them yourself.

- {% tool "codemeta" %} --- [Wizard link](https://codemeta.github.io/codemeta-generator/) 
- {% tool "cff" %} --- [Wizard link](https://citation-file-format.github.io/cff-initializer-javascript/#/)


### 6. Create a workflow release

Follow the [instructions on GitHub](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases) to create a workflow release and tag.


### 7. Now that the hard part is completed, [register the workflow](new_workflow)

