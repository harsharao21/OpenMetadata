# 1.6.6 Release 🎉

{% note noteType="Tip" %}
**Mar 14th, 2025**
{% /note %}

{% inlineCalloutContainer %}
{% inlineCallout
color="violet-70"
icon="celebration"
bold="Upgrade OpenMetadata"
href="/deployment/upgrade" %}
Learn how to upgrade your OpenMetadata instance to 1.6.6!
{% /inlineCallout %}
{% /inlineCalloutContainer %}

You can find the GitHub release [here](https://github.com/open-metadata/OpenMetadata/releases/tag/1.6.6-release).

- Improvements:- Added loggedInAPI to show more specific error messages instead of generic ones
- Added support for \`/logout\` path to perform logout from API redirect
- Added displayName field in the \`createCustomProperty\` schema
- Improved search relevancy for plural/singular words and partial matches
- Introduced "clear sample" option in entity config to support explicit null
- Made domain a required field for Data Product creation
- Enabled showdown rendering options`,
- Added support for datatype=array without type consistency
- Added result_maker check for query share URL in Looker
- Fixes:- Fixed Snowflake ARRAY column ingestion issues
- Fixed Sigma workbook ingestion
- Fixed tomcat-jdbc dependency
- Fixed schema URL construction
- Fixed Redshift view logging for no schema binding
- Fixed OpenMetadata Operations
- Supported request schema field for OpenAPI lineage when response field is absent
- Fixed tour page clicking issues
- Fixed duplicate activity feed providers
- Fixed search query for non-admin pages
- Fixed other columns visibility when testSuite name is large
- Fixed task description viewer for diff creation
- Fixed inherited owner not updating in Data Product list
- Fixed user update roles
- Fixed table constraint error
- Fixed manual constraints deletion
- Fixed deletion of entities
- Fixed entity relation live indexing
- Fixed service creation error display
- Fixed external app logs
- Fixed incremental lineage processing when processedLineage is null
- Improved memory handling in temp table lineage
- Enhanced Column Name Scanner
- Improved pipeline service client exception handling
- Updated Tableau documentation in Connectors
- Optimized pipeline service client initialization
- Implemented Incremental Lineage Processing
- Don't overwrite query to execute

**Full Changelog**: [link](https://github.com/open-metadata/OpenMetadata/compare/1.6.5-release...1.6.6-release)
