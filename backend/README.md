# Projects Node.js

Repository to handle the projects resource.

After cloning the project, run the command to install the dependencies:

```
yarn
```

To run the project:

```
yarn dev
```

The project will be available at `http://localhost:3333`.

## API

### GET /projects

USAGE: Get all projects.

### POST /projects

USAGE: Add a new project.

BODY:

```
title - String
owner - String
```

### PUT /projects/:id

USAGE: Edit the details of an existing project.

BODY:

```
title - String
owner - String
```

### DELETE /projects/:id

USAGE: Delete an existing project.
