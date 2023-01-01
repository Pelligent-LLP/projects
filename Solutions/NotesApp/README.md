# Resource Library
An intuitive, privacy-first, self-hosted, notes-taking application.

# Features
- Choice to host data storage
    - Blob storage in Cloud platforms, File Storage (Google, Microsoft), on-premises FileSystems, etc. 
    - Backups in Databases. Yet to choose whether to use NoSQL, or SQl-based engine
    - Shared cloud could also be an choice. Need to think of ways we can securely containerize user data
- Choice to deploy
    - Solution to be deployable on a variety of platforms - AWS, GCP, Azure, On-Premises servers, etc.
- Support for Markdown
    - Ability to create rich, intuitive & highly illustrative documents having Markdown Engine in background.
    - Abstracting the Markdown layer from an enhanced User Experiencel; an option to enable Markdown editing for the enthusiastic ones can be provided.
- Collaboration
    - Multiple Users to be able to edit documents, RBAC for docs access.
    - User presence features like - online, offline, current position in the document
    - Sharable links of documents - inter users, global, with a group.
- Third Party Integrations
    - Since we would be using Markdown Engine in the background, app should ideally seamlessly integrate with other servcies using the same.
- Locale
    - Language & Region options
    - Local attributes like - currency, units.
- UX
    - Abstract Markdown's intimidating syntax for the day-to-day users.
    - Themes: Something as light as terminal profile settings yet as rich as Sublime Text's themes.
    - Templates: Templates for use-cases - Resumes, Brochures, SRS docs, SoW, etc.
    - Prebuilt components: Tables, Title, Caption, Subtitle, Bulleted lists, Fonts, Shapes, Charts, DAGs, etc.
    - Directory/Page structure: Something like Confluence's Page order
