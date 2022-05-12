![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)
SPDX-License-Identifier: CC-BY-4.0

# Contributing to OpenDataology

Thank you for your interest in contributing to OpenDataology. This document explains the various ways in which you can get involved and contribute (and we'd love your help!)

* Give our repos a star (gets us motivated!)
* Join our [Slack](https://join.slack.com/t/dataset-license/shared_invite/zt-1823jgzvb-3ExLy22G4fKSaTYdXb9fYQ) channel to ask questions, clarifications, give us feedback, discuss collaborations or help us with answering questions from the community (we would love your company and we promise that we don't bite)
* If you notice an issue in our project- report it! Submit an [issue](https://github.com/OpenDataology/OpenDataology/issues)
* Fix or enhance our documentation (Submit a PR) -- we would really appreciate it submit. 
* If you notice a [new dataset license](Notify-us-of-a-license) (see here to understand what can consistitute as a dataset license) please let us know by submitting a PR to our dataset licenses repo 
* If you have legal expertise and wish to help us with [Decomposing the rights and obligations associated with a license](#Submit-a-rights-and-obligations-decomposition) from our available licenses list in to our enhanced Montreal Data License format or want to help analyze the potential [final rights and obligations associated](#submit-final-rights-and-obligations-of-a-dataset) with a dataset per our process
* Fix an [issue](#How-to-Contribute-a-Bug-Fix-or-Change) or submit a change.


For a description of the roles and responsibilities of the various members of the OpenDataology community, see the [Governance policies](https://github.com/OpenDataology/OpenDataology/blob/main/GOVERNANCE.md). Briefly, Contributors are anyone who submits content to the project, Committers review and approve such submissions, and the Technical Steering Committee provides general project oversight. Please note that all contributer 

If you just need help or have a question, refer to [SUPPORT.md](SUPPORT.md).


## How to Contribute a Change or a fix to an issue

To contribute code to the project, first read over the [governance policies](GOVERNANCE.md) page to understand the roles involved. 

Each code contribution must meet the [coding style] and include.

* Tests and documentation to explain the functionality.
* Any new files have [copyright and license headers](LICENSE.md)
* A [Developer Certificate of Origin signoff](what-is-the-dco.md).
* Submitted to the project as a pull request.
* If the change is to fix an issue, include the Issue number in both your pull request and commit message. 

If contribution is a documentation fix or with the decomposition of rights and obligations associated with a license 
* Any new files have [copyright and license headers]
* A [Developer Certificate of Origin signoff].
* Submitted to the project as a pull request.
* If the change is to fix an issue, include the Issue number in both your pull request and commit message. 
* Explnation of rationale or sources to back your claim for non-trivial contributions

OpenDataology is licensed under the [MIT License](LICENSE.md) license. Contributions should abide by that standard license.
Project committers will review the contribution in a timely manner, and advise of any changes needed to merge the request.
## Notify us of a new dataset license

please submit a PR to the common dataset licenses repo and mention the source of the dataset license in the PR.  A license may take various forms. It could be one of the widely approved licenses like MIT License, CC-BY-4.0 license or a comprehensive terms of use or user agreement or sometimes simply a casual note. All of these consistitute as license.

## Help with decomposition of a license

Most publicly available datasets or data sources from which the datasets are typically created come with a license. We have noted down several of these licenses in our common dataset licenses repository. You could help us decompose the rights and obligations associated with each license. If you wish to do so, we recommed that you submit a PR with the following details
* PR should contain the name/id of the license being decomposed. 
* The PR should clear note any ambiguites that the contributer might feel regarding the confidence of any right or obligation that was represented
* The PR should contain the rights and obligations decomposed using the CSV file provided in repo or here (which follows our enhanced Montreal data license format)

## Help with analzing the final rights and obligations associated with a dataset

If you wish to contribute to analyzing the final rights and obligations associated with a publicly available dataset you can do so by strictly following these steps.
* Ensure that you follow the dataset license analysis process that we outline [here]()
* Ensure you document the provenance of the dataset using our dataset provenance table (provided here as a CSV)
* Ensure that you capture the dataset's lineage using the dataset lineage table CSV (provided here) and the provenance of each datasource identified using the dataset provenance table used earlier
* Decompose the dataset license of the dataset and all of the sources indicated in the dataset lineage table in to rights and obligations associated as suggested here. 
* Finally record the final rights and obligations associated with a given dataset using our enhanced Montreal data license schema (CSV provided here)
* Submit the data provenance table (for both the dataset and the data sources identified in the lineage table), lineage table, enhanced montreal data license details for the dataset and each of the data sources and the final enhanced montreal data license details -- all of them as CSV files and attach them to the PR


## Getting your Changes approved

Your pull request must be approved and merged by a committer.



----
License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/),
Copyright Contributors to the OpenDataology project.
