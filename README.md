# VS Code Marketplace

VS Code Marketplace is Microsoft's official extension marketplace for Visual Studio Code, offering thousands of extensions for languages, debuggers, themes, and developer tools. It provides a Gallery API for programmatically searching, discovering, and retrieving extension metadata, enabling integration with editors, tooling, and automation workflows.

**Website:** https://marketplace.visualstudio.com/  
**Type:** 3rd-Party API Provider  
**Tags:** Developer Tools, Extensions, IDE, Marketplace, Microsoft, Visual Studio Code

---

## APIs

| API | Description | Base URL |
|-----|-------------|----------|
| [VS Code Marketplace Gallery API](https://marketplace.visualstudio.com/) | Search, discover, and download VS Code extensions | `https://marketplace.visualstudio.com/_apis/public/gallery` |

---

## OpenAPI Specifications

- [vs-code-marketplace-gallery-api-openapi.yml](openapi/vs-code-marketplace-gallery-api-openapi.yml) — VS Code Marketplace Gallery API (extension query, download, publisher)

---

## Spectral Rules

- [vs-code-marketplace-rules.yml](rules/vs-code-marketplace-rules.yml) — Spectral ruleset enforcing Gallery API conventions

---

## Naftiko Capabilities

### Shared Per-API Definitions

| File | API |
|------|-----|
| [shared/gallery-api.yaml](capabilities/shared/gallery-api.yaml) | VS Code Marketplace Gallery API |

### Workflow Capabilities

| File | Description | APIs Combined |
|------|-------------|---------------|
| [extension-discovery.yaml](capabilities/extension-discovery.yaml) | Search, filter, and discover VS Code extensions | Gallery API |

---

## JSON Schema

- [vs-code-marketplace-extension-schema.json](json-schema/vs-code-marketplace-extension-schema.json) — Schema for VS Code extension objects from the Gallery API

---

## JSON Structure

- [vs-code-marketplace-extension-structure.json](json-structure/vs-code-marketplace-extension-structure.json) — Gallery API request/response structure documentation

---

## JSON-LD

- [vs-code-marketplace-context.jsonld](json-ld/vs-code-marketplace-context.jsonld) — Linked data context for VS Code Marketplace

---

## Examples

- [vs-code-marketplace-queryExtensions-example.json](examples/vs-code-marketplace-queryExtensions-example.json) — Search extensions by keyword
- [vs-code-marketplace-downloadExtension-example.json](examples/vs-code-marketplace-downloadExtension-example.json) — Download a VSIX extension package

---

## Vocabulary

- [vs-code-marketplace-vocabulary.yml](vocabulary/vs-code-marketplace-vocabulary.yml) — VS Code extension ecosystem vocabulary

---

## Resources

| Resource | URL |
|----------|-----|
| Website | https://marketplace.visualstudio.com/ |
| Documentation | https://code.visualstudio.com/docs |
| Extension API | https://code.visualstudio.com/api |
| Publishing Guide | https://code.visualstudio.com/api/working-with-extensions/publishing-extension |
| Publisher Management | https://marketplace.visualstudio.com/manage |
| Extensions Catalog | https://marketplace.visualstudio.com/VSCode |
| GitHub | https://github.com/microsoft/vscode |
| Community | https://code.visualstudio.com/community |
| Terms of Use | https://marketplace.visualstudio.com/policies/agree |
| Privacy Policy | https://privacy.microsoft.com/privacystatement |

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
