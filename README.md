# MS-Paint-in-C
This project features a comprehensive MS Paint-style application built in C, providing users with diverse creative tools and capabilities. The program enables creation, editing, saving, and manipulation of various shapes—including geometric figures, letters, and numerals—along with freehand drawing functionality for unrestricted artistic expression.

The application follows the Model-View-Controller (MVC) architectural pattern for structured development. Inside the "Data" directory, multiple files are organized:

.c files contain the shape-drawing logic.

.h files hold their corresponding definitions.

"data_header.h" acts as the primary header file, consolidating necessary dependencies.

The "Brain" folder includes three key files:

"Brain.c" determines which shape to invoke from "data.c" based on user input.

"brain.h" provides function and structure definitions.

"brain_header.h" aggregates all required header files for seamless integration.

Within the "Interface" directory, another set of three files handles user interaction:

"Interface.c" processes input parameters such as color, size, position, and symbols.

"interface_header.h" combines essential headers for the interface components.
