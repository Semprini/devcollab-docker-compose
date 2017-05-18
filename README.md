# devcollab-docker-compose
Composable docker definitions which includes the entire development toolset.

Services have soft affinity to hosts with label collab=true and a soft affinity to spread multiple nodes of the same service accross VMs

First composition is an Atlassian based toolset and includes:
 - Crowd (Identity and Access management)
 - Jira (Issue and Project tracking)
 - Bitbucket (Source code repo)
 - Sonarqube (Code evaluation)
 - Confluence (Documentation and Wiki)
 - Nexus (Artefact repository)
 - Bamboo (CI/CD)
 - Postgresql (Database)

This composition will require licences for the Atlassian tools (10 users will cost $50 for all apps)
