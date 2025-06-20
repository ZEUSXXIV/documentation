# Making a Dependency Diagram (Redgate SQL Dependency Tracker)

This document summarizes how to create and configure dependency diagrams using Redgate SQL Dependency Tracker. Dependency diagrams help visualize relationships and dependencies between SQL Server database objects, making it easier to understand and manage complex databases.

## Creating a Dependency Diagram

To create a new dependency diagram:

1. **Start a New Project:**  
   Open SQL Dependency Tracker and select **New Project**.
2. **Add Databases/Objects:**  
   Choose the databases and objects you want to include in the diagram.
3. **Visualize Dependencies:**  
   The tool will automatically display objects and their dependencies in a graphical format.
4. **Customize the Layout:**  
   Rearrange, group, and format objects as needed.

---

## 1. Diagram Options

Diagram options allow customization of how dependencies and objects appear in your diagram.

- **Show/Hide Dependencies:** Toggle the visibility of specific types of dependencies, such as triggers, foreign keys, or custom relationships.
- **Layout Options:** Choose automatic or manual arrangement of objects. Use features like Auto Layout or arrange objects freely.
- **Object Display:** Control which details are shown (e.g., object names, types, schema).
- **Grouping:** Group related objects for clarity.
- **Highlighting:** Emphasize specific objects or dependencies.
- **Zoom and Pan:** Navigate large diagrams easily.
- **Filter:** Show or hide objects based on criteria (object type, schema, etc).

---

## 2. Project Options

Project options control overall project settings and behavior:

- **Database Connection Settings:** Manage credentials and connection info for source databases.
- **Object Selection:** Choose which database objects to include or exclude.
- **Refresh Options:** Set how and when the diagram updates if the source database changes.
- **Save/Load Projects:** Save your diagram as a project file for future use or sharing.
- **Export Options:** Export diagrams as images, PDFs, or other formats.
- **Diagram Properties:** Set properties like project name, description, and author.
- **Dependency Rules:** Define which dependency types are included.

---

**References:**  
- [Making a Dependency Diagram - Redgate Documentation](https://documentation.red-gate.com/sdt3/making-a-dependency-diagram)  
- [Diagram Options](https://documentation.red-gate.com/sdt3/making-a-dependency-diagram/diagram-options)  
- [Project Options](https://documentation.red-gate.com/sdt3/making-a-dependency-diagram/project-options)