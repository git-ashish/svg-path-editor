# SvgPathEditor
Edit or create SVG paths in browser: https://yqnn.github.io/svg-path-editor/
[![Image of Yaktocat](./doc/screenshot.png)](https://yqnn.github.io/svg-path-editor/)

## How to Use

##### Basic:
- Paste or edit the raw path in the **path** field
- Click on **+** to add a new command to the path, select a type, then click on the destination
- Move points with drag and drop
- Click on a point, then on the **+** to insert a command right after the selected one

##### Commands panel:
- Click on the command type to toggle between relative and absolute coordinates
- Relative command types are **orange**, absolute are **purple**
- Click on **...** then **Delete** to delete a command
- Click on **...** then **Insert after** to insert a new command right after the selected one
- Click on **...** then **Convert to** to convert the selected command to a new type

##### Viewport:
- Use mouse wheel to zoom in/out
- Use drag & drop to move the viewport
- Click on **AUTO** to automatically set the viewport depending on current path
- Viewport can also be set manually with the **x**, **y**, **width** and **height** fields

##### Path operations:
- Scale the full path with the **Scale** button
- Translate the full path with the **Translate** button
- Round all coordinates of the current path with the **Round** button
- Convert all commands to relative or absolute coordinates with **Convert to relative** or **Convert to absolute** button

## Running Locally

##### Requirements
- [Node.js](https://nodejs.org/) v12.0 or higher

##### Dependencies
Run `npm install` to retrieve all the depencies of the project.

##### Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

##### Build
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

##### Running unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.3.
