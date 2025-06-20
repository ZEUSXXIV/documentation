# Understanding the Diagram

[Read the full documentation](https://documentation.red-gate.com/sdt3/understanding-the-diagram)

The diagram provides a visual representation of your database schema or project structure. Each object (such as tables, views, stored procedures) is shown as a box, and relationships (such as foreign keys) are represented as connectors between these boxes. The main uses of the diagram are:

- **Visualizing dependencies:** Easily see how objects are related and dependent on each other.
- **Understanding structure:** Get a quick overview of the organization and complexity of your database or schema.
- **Identifying issues:** Spot potentially problematic relationships or missing connections.

The diagram may use different shapes, colors, or icons to represent different object types and their states (for example, whether an object is newly modified, or unchanged).

---

# Object Details

[Read the full documentation](https://documentation.red-gate.com/sdt3/understanding-the-diagram/finding-out-more-about-an-object)

To learn more about a specific object in the diagram:

- **Hover over an object** to see a tooltip with summary information (such as the object type and name).
- **Click on an object** to open a detailed pane or dialog, which typically includes:
  - The object's definition or script (such as the CREATE statement for a table).
  - Properties such as columns, data types, indexes, and constraints (for tables).
  - Dependency information: which objects reference this one, and which objects it references.
  - Additional metadata, such as schema, owner, or modification date.

This allows you to quickly drill down into any object, understand its structure, and see how it fits into the overall system.

---

# Navigating the UI

[Read the full documentation](https://documentation.red-gate.com/sdt3/understanding-the-diagram/navigating-the-user-interface)

The user interface for the diagram provides several features to help you explore complex schemas efficiently:

- **Zoom and Pan:** Use mouse controls or UI buttons to zoom in/out and pan across the diagram, making it easier to focus on specific areas.
- **Mini-map or Overview Panel:** A smaller overview panel may be available to show your current location within a large diagram and allow quick navigation.
- **Object Browser or List:** Use a panel or sidebar to locate and select objects by name, especially helpful in large diagrams.
- **Search:** Enter part of an object’s name to highlight it in the diagram.
- **Highlighting:** When you select or hover over an object, related objects (such as those with dependencies) are highlighted to show their connections.
- **Layout Controls:** Switch between different layout algorithms to organize the diagram in the way that best suits your needs.

---

# Selecting Objects

[Read the full documentation](https://documentation.red-gate.com/sdt3/understanding-the-diagram/selecting-objects)

Selecting objects in the diagram enables you to:

- **View detailed information:** Selecting one or more objects brings up their properties, definitions, and dependencies.
- **Edit or compare objects:** Use selection to perform comparison or synchronization tasks, or to modify object properties (if editing is enabled).
- **Multi-selection:** Hold down the Ctrl or Shift key (or use selection tools in the UI) to select multiple objects at once.
- **Contextual actions:** Right-clicking on selected objects may bring up a context menu with actions such as generating scripts, viewing differences, or navigating to related objects.

Careful selection and inspection are essential for tasks like change impact analysis, schema comparison, or object-level deployment.

---