# issues

Issues for the project are often difficult for users/issue reporters to report in the correct repository.  Is an issue on OpenStates.org a data issue? An issue with the site itself, perhaps the API?    

By unifying the issues repositories for the various components, it is much easier for people to report issues and for us to manage issues without relying on moving them around & making them harder to find.  If you're reporting an issue, just do your best :), we'll retag as needed.

[Issues without Type](https://github.com/openstates/issues/issues?q=is%3Aissue+is%3Aopen+-label%3Atype%3Aenhancement+-label%3Atype%3Ahistorical+-label%3Atype%3Abug+-label%3Atype%3Aupstream+-label%3Atype%3Aproposal)

[Issues without Component](https://github.com/openstates/issues/issues?q=is%3Aissue+is%3Aopen+-label%3Acomponent%3Abill-data+-label%3Acomponent%3Aweb+-label%3Acomponent%3Aapi-v3+-label%3Acomponent%3Apeople-data+-label%3Acomponent%3Ainfrastructure)


If you're mentioning issues in this repo in a commit message, do so as openstates/issues#issue-num

There are a few types of tags used, component: and type: are the most common.

## Type Tags

Issues are typically assigned one of the following types:

* type:bug
* type:upstream
* type:proposal
* type:historical

## Component Tags

Tags beginning with component: indicate which part of Open States the issue is in.  If you're looking to work on a particular portion of the project, they can be helpful in limiting the scope.  A mapping of the components to repositories is presented below:

component                        | repo                                              | description
---------------------------------|---------------------------------------------------|--------------
component:api-v3                 | https://github.com/openstates/simpleapi           | planning for the upcoming API v3
component:web                    | https://github.com/openstates/openstates.org      | non-data issues related to OpenStates.org or older APIs
component:bill-data              | https://github.com/openstates/openstates-scrapers | incorrect or incomplete bill & vote data
component:people-data            | https://github.com/openstates/people              | incorrect or incomplete legislator data
component:infrastructure         | https://github.com/openstates/openstates-core     | related to core infrastructure
