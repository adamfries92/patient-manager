# patient-manager OpenAPI Spec

## DISCLAIMER

This API specification and tooling is based on the template structure defined
[here](https://github.com/dgarcia360/openapi-boilerplate)

## Useful commands

The project will build, lint, and preview the OpenAPI document from the terminal, with the following commands:

### Build

The command bundles the spec as one `.yaml` file.

```bash
npm run build
```

The minified document is stored in `_build/openapi.yaml`.

### Test

The command checks if the document follows the OpenAPI 3.0 Specification.

```bash
npm run test
```

### Preview

The command builds a docs site so that you can view the rendering on your local browser.

```bash
npm run preview
```

The server starts on `http://127.0.0.1:8080`.

The site is generated with [ReDoc](https://github.com/Redocly/redoc).
Here's a preview of a site generated with this command: [Swagger Petstore Reference Documentation](https://dgarcia360.github.io/openapi-boilerplate/).
