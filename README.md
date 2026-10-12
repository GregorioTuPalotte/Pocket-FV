Pocket

Pocket is an Android file explorer built with Python and Kivy that combines a traditional file browser with visual graph-based navigation.

Vision

Explore and manage files through a minimal, fast, and mobile-friendly interface.

Its main feature is a graph where folders are represented as connected nodes. In the long term, the graph will represent the entire accessible storage of the device.

Planned Features

Graph View

- Represent folders as connected nodes.
- Adjust node sizes based on the number of items or connections.
- Enter a folder by tapping its node.
- Return to the graph by swiping right.
- Explore the entire storage through the graph once the required functionality is implemented.

File View

- Display files and folders in a list.
- Filter files by type within the current directory.
- Select one or multiple items.
- Open files or choose which application to open them with.
- Create files and directories.
- Rename, move, and delete items.
- View file and directory details.

Planned Technologies

- Python
- Kivy
- Git

Storage access will be designed with Android's restrictions in mind.

Planned Stages

1. Document the concept and define the basic behavior.
2. Test file and directory management logic.
3. Build a Graph View prototype using mock data.
4. Implement the File View.
5. Integrate both views.
6. Investigate Android storage access and APK building.
7. Test and optimize the application on the actual device.

Current Status

In the planning stage. The features described above are goals, not yet implemented functionality.