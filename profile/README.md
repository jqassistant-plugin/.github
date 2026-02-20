# Welcome to jQAssistant-Plugin 👋

jQAssistant is an Open-Source-Tool that helps you to analyze and control the quality of your software systems.
Its plugin-based architecture allows the user to adapt jQAssistant to the needs of the analyzed project by adding

* scanner plugins to support additional file formats
* rule plugins to support frameworks, technologies, and libraries as well as common architectural and design patterns
* report plugins to support the reporting of results in new formats

## About the organization

This GitHub organization provides a collection of useful extensions to jQAssistant (
see [repositories](https://github.com/orgs/jqassistant-plugin/repositories)).

The core jQAssistant distribution is developed in our [main organization](https://github.com/jqassistant).
Please have a look there for general information and when having issues or feature requests.

Examples and tutorials can be found in our [examples organization](https://github.com/jqassistant-tutorials).
We recommend that every (new) user takes a look at it and be inspired.

## Plugins

| Category                      | Plugin                    | Description                                                                                                              | Repository                                                                  |
|-------------------------------|---------------------------|--------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| Java                          | Java Testing Plugin       | Rules for test Javas frameworks, e.g. Mockito, AssertJ, Hamcrest                                                         | https://github.com/jqassistant-plugin/jqassistant-java-testing-plugin       |
|                               | JEE Plugin                | Rules for Java EE and Jakarta EE, e.g. for verifying dependency injection or transaction management                      | https://github.com/jqassistant-plugin/jqassistant-jee-plugin                |
|                               | jMolecules Plugin         | Rules to identify and validate architectural concepts in Java applications                                               | https://github.com/jqassistant-plugin/jqassistant-jmolecules-plugin         | 
|                               | MapStruct Plugin          | Rules for MapStruct (e.g. identification of generated code)                                                              | https://github.com/jqassistant-plugin/jqassistant-mapstruct-plugin          |
|                               | RDBMS Plugin              | Scanner for relational database schemas, e.g. tables, columns, foreign keys                                              | https://github.com/jqassistant-plugin/jqassistant-rdbms-plugin              |
|                               | Spring Plugin             | Rules for the Spring Framework, e.g. for verifying dependencies, dependency injection or transaction management          | https://github.com/jqassistant-plugin/jqassistant-spring-plugin             |
| TypeScript                    | NPM Plugin                | Scanner and rules for NPM based projects for dependency analysis                                                         | https://github.com/jqassistant-plugin/jqassistant-npm-plugin                |
|                               | TypeScript Plugin         | Scanner for TypeScript                                                                                                   | https://github.com/jqassistant-plugin/jqassistant-typescript-plugin         |
| API Contracts                 | AsyncAPI Plugin           | Scanner and rules for AsyncAPI contracts                                                                                 | https://github.com/jqassistant-plugin/jqassistant-asyncapi-plugin           |
|                               | GraphQL Plugin            | Scanner for GraphQL schemas                                                                                              | https://github.com/jqassistant-plugin/jqassistant-graphql-plugin            |
|                               | OpenAPI Plugin            | Scanner for OpenAPI contracts                                                                                            | https://github.com/jqassistant-plugin/jqassistant-openapi-plugin            |
| Models                        | C4 Plugin                 | plantuml-stdlib/C4-PlantUML integration for jQAssistant to scan C4 diagrams to validate as-is against to-be architecture | https://github.com/jqassistant-plugin/jqassistant-c4-plugin                 |
|                               | Context Mapper Plugin     | Scanner for Context Maps and rules to validate as-is against to-be architecture                                          | https://github.com/jqassistant-plugin/jqassistant-context-mapper-plugin     |
|                               | XMI Plugin                | Scanner for UML models in XMI files                                                                                      | https://github.com/jqassistant-plugin/jqassistant-typescript-plugin         |
| Visualization                 | CodeCharta Plugin         | Reports and rules for CodeCharta visualizations                                                                          | https://github.com/jqassistant-plugin/jqassistant-codecharta-plugin         | 
|                               | GraphML Plugin            | Report rule results as GraphML files for visualizatiob                                                                   | https://github.com/jqassistant-plugin/jqassistant-graphml-plugin            |
|                               | PlantUML Report Plugin    | Report rule results as PlantUML component or sequence diagrams                                                           | https://github.com/jqassistant-plugin/jqassistant-plantuml-report-plugin    |
| Tool Integration              | CodeClimate Report Plugin | Report for publishing jQAssistant analysis results to GitLab                                                             | https://github.com/jqassistant-plugin/jqassistant-codeclimate-report-plugin |
|                               | CycloneDX Plugin          | Scanner for CycloneDX files, e.g. SBOM                                                                                   | https://github.com/jqassistant-plugin/jqassistant-cyclonedx-plugin          |
|                               | NexusIQ Plugin            | Scanner and rules for NexusIQ reports                                                                                    | https://github.com/jqassistant-plugin/jqassistant-nexusiq-plugin            |
| Repositories & ticket systems | Docker Plugin             | Scanner for Docker registry metadata                                                                                     | https://github.com/jqassistant-plugin/jqassistant-docker-plugin             |
|                               | GitHub Plugin             | Scanner for GitHub repositories and issues                                                                               | https://github.com/jqassistant-plugin/jqassistant-github-plugin             |
|                               | JIRA Plugin               | Scanner and rules for JIRA boards and issues                                                                             | https://github.com/jqassistant-plugin/jqassistant-jira-plugin               |
|                               | M2 Repo Plugin            | Scanner for Maven artifact repositories, e.g. Sonatype Nexus, JFrog Artifactory                                          | https://github.com/jqassistant-plugin/jqassistant-m2repo-plugin             |
| DART (experimental)           | DART Plugin               | Scanner for DART (experimental)                                                                                          | https://github.com/jqassistant-plugin/jqassistant-dart-plugin               |
|                               | Pub Plugin                | Scanner for Pub based projects                                                                                           | https://github.com/jqassistant-plugin/jqassistant-pub-plugin                |

More plugins are available fromn [Kontext E Plugins for jQAssistant](https://github.com/orgs/kontext-e/repositories). 

## Way of contribution

We're happy about every contribution. To make this as efficient as possible, take a look at the following guidance:

* Issues should have a meaningful description, best with an example for reproduction. If possible to identify, put the issue into the repository of the part (
  e.g. core, a plugin, an example) where the issue occurred. This saves us a lot of time.
  * We're happy to accept pull requests that solve the issue.
* Feature Requests should have a meaningful description, best with an example. If possible to identify, put the feature request into the repository of the
  part (e.g. core, a plugin, an example) where you expect the feature to be. This saves us a lot of time.
  * We're happy to accept pull requests that implement the request.

For any other topics, feel free to [Contact Us](mailto:info@jqassistant.org)

## Further Information

* [User Manual](https://jqassistant.github.io/jqassistant/doc/)
* [Introduction to jQAssistant in JavaMagazin (german only)](https://www.buschmais.de/download/JavaMagazin_Artikelserie_jQAssistant.pdf)
* [jQAssistant Core](https://github.com/jqassistant)
* [jQAssistant Examples](https://github.com/jqassistant-tutorials)
