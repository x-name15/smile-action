# smile-action

Official GitHub Composite Action for [smile](https://github.com/x-name15/smile) — 
the relentless API contract linter for OpenAPI, AsyncAPI, GraphQL, gRPC, and Postman.

## Usage

```yaml
- uses: x-name15/smile-action@v1
  with:
    spec-path: "."
    format: "text"
    max-warnings: 0
```

Full documentation: https://github.com/x-name15/smile/blob/main/docs/ci-cd.md
