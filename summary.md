# SQL Dependency Tracker: Functional Document

## Visualizing and Navigating Database Structures

SQL Dependency Tracker provides a powerful way to visualize, explore, and manage the structure and dependencies within your SQL Server databases. At its core, it generates interactive diagrams that represent objects such as tables, views, and stored procedures as nodes, with lines showing their relationships (like foreign keys or references). This visual approach makes it easier to grasp complex schemas, understand interdependencies, and spot potential issues.

### Key Diagram Features

- **Visual Representation:**  
  Each database object appears as a box or icon, with different shapes, colors, or symbols indicating object types (e.g., table, view) and their states (e.g., newly modified, unchanged).

- **Dependency Mapping:**  
  Arrows or connectors show how objects are related, helping you instantly see which tables have foreign key relationships, which views depend on which tables, and more.

- **Highlighting & Focus:**  
  Selecting or hovering over an object highlights its direct dependencies and dependents, making it easy to trace impact or investigate relationships.

- **Mini-map/Overview Panel:**  
  Large diagrams can be hard to navigate, so a mini-map helps you keep track of your current focus area and quickly jump to other sections.

- **Search & Filtering:**  
  To manage large schemas, use the search bar to find objects by name. You can also apply filters to display only certain object types, schemas, or those matching specific criteria.

- **Layout & Customization:**  
  Diagrams can be automatically arranged or manually adjusted. Group related objects together, hide specific dependencies, or highlight areas of interest for presentations or analysis.

## Exploring Object Details

Getting in-depth information about any object in the diagram is straightforward:

- **Tooltips:**  
  Hovering over an object brings up a summary with its type and name.
  
- **Detail Pane:**  
  Clicking an object opens a detailed view showing its definition (such as the CREATE TABLE statement), columns, data types, constraints, indexes, and metadata like schema or last modification date.

- **Dependency Information:**  
  See which objects depend on the selected one, and which ones it depends on. This is crucial for understanding the ripple effect of changes.

- **Contextual Actions:**  
  Right-clicking on an object often brings up a menu with quick actions—generate a script, view differences, or navigate to related objects.

## Creating and Managing Projects

### Creating a Dependency Diagram

1. **Start a New Project:**  
   Launch SQL Dependency Tracker and select "New Project".

2. **Add Databases and Objects:**  
   Choose which databases and objects to include in your analysis. You can select entire databases or pick specific tables, views, or procedures.

3. **Visualize Dependencies:**  
   The tool automatically builds a diagram showing all selected objects and their relationships.

4. **Customize the Diagram:**  
   Rearrange objects, group related items, and adjust the layout to best suit your needs.

### Diagram and Project Options

- **Show/Hide Dependencies:**  
  Decide which types of relationships (e.g., triggers, foreign keys) are shown in the diagram.

- **Object Display Controls:**  
  Choose what details are visible for each object, such as name, type, or schema.

- **Grouping and Highlighting:**  
  Organize objects into logical groups, and highlight key objects or relationships for emphasis.

- **Zoom & Pan:**  
  Easily navigate large diagrams with zoom controls and panning.

- **Filter Objects:**  
  Show or hide objects based on defined criteria, such as schema, type, or custom tags.

- **Database Connection Settings:**  
  Manage credentials and connection info for your source databases.

- **Refresh Options:**  
  Set up how and when the diagram should update if the source database changes.

- **Save and Export:**  
  Save your diagram as a project file for future editing or collaboration, or export as images, PDFs, or other formats for sharing with stakeholders.

- **Dependency Rules:**  
  Define which types of dependencies to include in your analysis.

## Supported Platforms and Requirements

- **Operating Systems:**  
  - Microsoft Windows 10  
  - Microsoft Windows 11

- **Prerequisites:**  
  - SQL Server client-side tools  
  - Microsoft .NET Framework 4.7.2 or later

- **Supported SQL Server Versions:**  
  - SQL Server 2014, 2016, 2017, 2019  
  - Azure SQL Database & Virtual Machines  
  - SQL Server on Amazon RDS & Virtual Machines  
  - Google Cloud SQL for SQL Server & Virtual Machines

## Best Practices and Use Cases

- **Change Impact Analysis:**  
  Use the diagram to see how proposed changes (like altering a table) will affect downstream objects.

- **Schema Comparison:**  
  Quickly compare objects to spot differences or inconsistencies.

- **Deployment Planning:**  
  Identify dependencies and required deployment order to prevent errors during rollout.

- **Documentation and Communication:**  
  Export diagrams for inclusion in technical documentation or use them in meetings to communicate system structure with team members.

## References & Further Reading

- [Making a Dependency Diagram - Redgate Documentation](https://documentation.red-gate.com/sdt3/making-a-dependency-diagram)
- [Diagram Options](https://documentation.red-gate.com/sdt3/making-a-dependency-diagram/diagram-options)
- [Project Options](https://documentation.red-gate.com/sdt3/making-a-dependency-diagram/project-options)
- [Understanding the Diagram](https://documentation.red-gate.com/sdt3/understanding-the-diagram)