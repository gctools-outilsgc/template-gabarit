# Strategy for release notes on Open Accessible, Digital Workspace applications. 

Currently in draft. 

## Release Notes and Versions

Release notes provide a detailed summary of all changes to a particular repository and application. Releases (versions) allow users, contributors and product owners (i.e. our team) to understand how an application has progressed since the first release (i.e. the MVP of an application). 

### Versioning

Regardless of whether an application is in beta, pilot, or full production, versions help identify specific points of progression on an application. Versions provide a snapshot of a code repository at a given point in time, and help identify major changes or updates to an application. Versioning demonstrates gradual progression that is more granular and specific than just alpha, beta or production. 

Versioning applications also helps with project management. Certain fixes or additions can be identified for specific versions, which will help categorize and prioritize issues on the given repository. Github Milestones can then be created to better assign, manage and track progress of particular issues. Versions provide a checkpoint for product owners to reference work completed within Pull Requests, and approve communications to users (content in release notes).

Versions also serve the purpose of communicating progress to contributors and users. Individuals who have been following or using the application for some time, will be better able to understand the progress of the application since first launch. Version numbers can also be used strategically to communicate regular changes (i.e. moving from v 0.1.2 to 0.1.3) or more significant updates to an application (moving from v 0.1.2 to v 0.2). 

### The purpose of release notes

Release notes are written based on Pull Requests, and give a detailed description of all commits and Pull Requests that were made during a certain time period (versions). These descriptions should provide enough detail so that a developer has an accurate picture of what changes were made to an application.  Using release tags also allows developers to return to previous versions of a repository, for better change management of code. 

Release notes also serve as a communications tool for contibutors and users. Notes should be written in simple enough language that users can get a quick summary of new or removed features, improvements, and bug fixes. Versioning helps users understand how long an application has been in production, and the progress since first launch. By providing detailed release notes and versions, contributors (developers or otherwise), can return to a project at any time, and understand the progress of an application since their last contribution. Contributors can also keep tabs on the progress of an application, and contribute when it makes sense to them, without falling "out of the loop" on application progress. 

## Github Release feature ( https://github.com/{repo}/releases )
A Github Release is, technically, nothing more than a README for a named point in the history of the repo (a tag) combined with some attached files. By default a Release will have attached the repo's files from the point in history of the selected tag  in compressed file - .zip and .tar.gz formats. Additional files can be added to the Release as needed. Releases can also be marked as pre-releases to indicate they are not final or a release candidate undergoing review.

While it doesn't look like Releases can be templated the same way that Issues and Pull Requests can be, a similar if limited effect can be achieved using form parameters in a url (eg. https://github.com/gctools-outilsgc/template-gabarit/releases/new?body=Test+Release). A simpler and more automated way to handle releases is to of course automate most of the process using the Github API. The full or near-full automated approach provides the additional benefits of consistency and only needing to review and edit the releases manually, however it also requires some organizational effort depending on what the Releases are meant to communicate ( for example, a consistent and descriptive commit history or Pull Request title if they are to be used to populate a change log section in automated releases).

## How to implement release notes on new repositories

Since release notes are based on Github Pull Requests, developers and contributors should be providing clear and informative titles and full descriptions on all Pull Requests. Pull Request templates are available in this Templates repository. 

Before publishing release notes with a new version number, a member of the User Experience team will review the individual logs for written clarity, though minimal edits should be required. 

Product owners should sign off on the new version (i.e. all Pull Requests and release notes) before the Milestone is closed, the version is pushed to production, and release notes are published. 

## What to capture in release notes

Release notes should be a detailed list of all Pull Requests related to that version of the application. Release notes should be written in a way that provides enough information for developer to accurately recount changes, but also simple enough for common users of the application to understand new updates that are made. 

In general, release notes should fall under these headers: Additions, Removals, Changes, Fixes. 

Since release notes are based on Pull Requests, Pull Requests should identify which part of the application is being changed (i.e. which feature) and whether it is an addition, removal, improvement or bug fix. Information about each specific change will depend on which details are provided in the Pull Request. If more information is needed, the author of the release notes can also reference specific commits within the Pull Request. 

## When to post release notes (versioning)

New versions for applications can be decided by the product owner. In general, versions may follow either a set sprint schedule (i.e. two sprints) or be based on a set number or significance of changes made to the application. We do not need to push a new version of an application every sprint, and not all applications need to follow the same versioning schedule. 

Versions can be integrated into our workflow using Milestones. Milestones are a Github feature that can be used to group together certain issues, categorize them, and set a target date to have said issues completed. Milestones can be created for each version of the application we want to release, and when a Milestone reaches 100% completion, we can then push the changes to production along with release notes. 

## When should release notes be more actively communicated to users?

Release notes should be reviewed by a member of the User Experience team before being posted. Any major updates that should be more actively communicated to users should be identified and actioned by the Content Strategist or Technical Writer in the User Experience team. Some releases (i.e. major feature updates or launch of a new product) should also be communicated by the Advocacy team. 

Broader user communications should be actioned on the following releases:

* Significant changes to the user experience of an application
* Major bug fixes that have an impact on the end user. 
* New features
* Front-end design changes

The following should also include communications from the Advocacy team:

* New product launches
* Addition of major features or iterations to existing applications
* Any other change or update that has a major user impact and promotes the OADW project as a whole
