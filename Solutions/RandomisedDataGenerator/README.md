# Resource Library
A utility to generate highly relative data for a given subject, topic or domain. Another feature would be to strip off identifying attributes from user data & using aggregated analytics, or giving pseudonyms to users.

## Features
- Context
    - An interface to provide subject, topic or domain context. For example, to generate random data for a billing system, we would need certain entity, attributes and their relationships as context input.
    - This context can provided in the form of SQL schema for now. More standard can come in later. Possibly Parsing of UMLs can be a nice intuitive way.
- Generator
    - Data generation based on the provided context.
    - An engine that is capable of doing the following
        - Understading types of data: people, region, currency, phone, email, address, etc.
        - Ability to plug data format: json, xml, yaml, sql, programming languages(Java, Python, Go, etc.)
        - Extensibility in terms of types & formats of data.
- Storage
    - Ability to create and maintain datasets for future use.
    - Ability to build scenarios and then scenario specific data.
- Integration
    - Import/Export APIs for datasets
    - Consumption Layer for Context
- Randomiser
    - Randomising an input dataset to strip off identifying data.
    - Intake identifying attributes as input
    - Identifying algorithm for identifying attributes & replacing with pseudonyms
    - Ability to aggregate data for analytics over a set rather than individuals. Belief is - a trend seen as a group is also applicable to some-percentage to individuals as well. Individual targetting of products or services should not happen.

## References
[Techopedia: Test Data Generator](https://www.techopedia.com/definition/30405/test-data-generator#:~:text=A%20test%20data%20generator%20is,to%20create%20a%20desired%20result)
