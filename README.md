# Supermodel API Documentation

Source for the Supermodel API docs site: [docs.supermodeltools.com](https://docs.supermodeltools.com).

## Get an API key

Get your API key from the [Supermodel Dashboard](https://dashboard.supermodeltools.com/) and send it in the `X-Api-Key` header.

## Quickstart

- **Docs**: [docs.supermodeltools.com](https://docs.supermodeltools.com)
- **OpenAPI spec (canonical)**: [`supermodeltools/openapi-spec`](https://github.com/supermodeltools/openapi-spec) (`openapi.yaml`)
- **TypeScript SDK**: [`supermodeltools/typescript-sdk`](https://github.com/supermodeltools/typescript-sdk)
- **MCP Server**: [`supermodeltools/mcp`](https://github.com/supermodeltools/mcp)

## Updating docs and API reference

- **Pages**: edit the MDX files in the repo root (`index.mdx`, `quickstart.mdx`, `authentication.mdx`, `concepts.mdx`).
- **API Reference**: this site is driven by the public OpenAPI spec in [`supermodeltools/openapi-spec`](https://github.com/supermodeltools/openapi-spec).

## Accuracy policy

- **Production-first**: examples should target `https://api.supermodeltools.com` and the Dashboard at [dashboard.supermodeltools.com](https://dashboard.supermodeltools.com/).
- **Spec mismatch?** If the API behavior differs from the spec, file an issue on [`supermodeltools/openapi-spec`](https://github.com/supermodeltools/openapi-spec).
- **Docs issue?** File an issue on this repo.

## Support

- **Email**: `mailto:engineers@supermodel.software`

## Local development (docs repo only)

These instructions are only for previewing changes to `supermodel-api-docs` locally.

Install the `mint` CLI:

```bash
npm i -g mint
```

Run the dev server from this repo root (where `docs.json` lives):

```bash
mint dev
```

Preview at `http://localhost:3000`.
