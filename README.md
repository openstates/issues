# issues

Issues for the project are often difficult for users/issue reporters to report in the correct repository.  Is an issue on OpenStates.org a data issue? An issue with the site itself, perhaps the API?    

By unifying the issues repositories for the various components, it is much easier for people to report issues and for us to manage issues without relying on moving them around & making them harder to find.  If you're reporting an issue, just do your best :), we'll retag as needed.

There are a few types of tags used, component: and type: are the most common.

## Type Tags

Issues are typically assigned one of the following types:

* type:bug
* type:upstream
* type:proposal
* type:enhancement
* type:historical

[Issues without Type](https://github.com/openstates/issues/issues?q=is%3Aissue+is%3Aopen+-label%3Atype%3Aenhancement+-label%3Atype%3Ahistorical+-label%3Atype%3Abug+-label%3Atype%3Aupstream+-label%3Atype%3Aproposal)

## Component Tags

Tags beginning with component: indicate which part of Open States the issue is in.  If you're looking to work on a particular portion of the project, they can be helpful in limiting the scope.  A mapping of the components to repositories is presented below:

component                        | repo                                              | description
---------------------------------|---------------------------------------------------|--------------
component:api-v1                 | https://github.com/openstates/openstates.org      | issues specific to the legacy v1 API
component:api-v2                 | https://github.com/openstates/openstates.org      | issues specific to the GraphQL v2 API
component:api-v3                 | https://github.com/openstates/simpleapi           | planning for the upcoming API v3
component:website                | https://github.com/openstates/openstates.org      | non-data issues related to OpenStates.org
component:bill-data              | https://github.com/openstates/openstates-scrapers | incorrect or incomplete bill & vote data
component:bill-infrastructure    | https://github.com/openstates/openstates-scrapers | incorrect or incomplete bill & vote data
component:text-extraction        | https://github.com/openstates/text-extraction     | full text extraction infrastructure
component:geo                    | https://github.com/openstates/openstates-geo      | incorrect GIS data
component:people-data            | https://github.com/openstates/people              | incorrect or incomplete legislator data
component:people-infrastructure  | https://github.com/openstates/people              | incorrect or incomplete legislator data
component:documentation          | https://github.com/openstates/documentation       | documentation corrections & improvements

