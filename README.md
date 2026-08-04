# VS Code Marketplace (vs-code-marketplace)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

VS Code Marketplace is Microsoft's official extension marketplace for Visual Studio Code, offering thousands of extensions for languages, debuggers, themes, and developer tools. It provides a Gallery API for programmatically searching, discovering, and retrieving extension metadata, enabling integration with editors, tooling, and automation workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Developer Tools
- Extensions
- IDE
- Microsoft

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### VS Code Marketplace Gallery API

The VS Code Marketplace Gallery API provides programmatic access to the Visual Studio Marketplace, enabling search, discovery, and retrieval of extensions for Visual Studio Code and other Microsoft developer tools. It supports querying extensions by name, publisher, category, and tags, as well as fetching extension details, versions, statistics, and reviews.

- **Human URL:** [https://github.com/microsoft/vscode/blob/main/src/vs/platform/extensionManagement/common/extensionGalleryService.ts](https://github.com/microsoft/vscode/blob/main/src/vs/platform/extensionManagement/common/extensionGalleryService.ts)
- **Base URL:** `https://marketplace.visualstudio.com/_apis/public/gallery`

#### Tags

- Developer Tools
- Extensions
- IDE
- Marketplace
- Microsoft
- Visual Studio Code

#### Properties

- [Documentation](https://marketplace.visualstudio.com/)
- [Base U R L](https://marketplace.visualstudio.com/_apis/public/gallery)
- [Source Code](https://github.com/microsoft/vscode/blob/main/src/vs/platform/extensionManagement/common/extensionGalleryService.ts)
- [Guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/openapi/vs-code-marketplace-gallery-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vs-code-marketplace-gallery-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vs-code-marketplace-gallery-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://marketplace.visualstudio.com/)
- [Documentation](https://code.visualstudio.com/docs)
- [Guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)
- [Portal](https://marketplace.visualstudio.com/manage)
- [Documentation](https://code.visualstudio.com/api)
- [Getting Started](https://code.visualstudio.com/api/get-started/your-first-extension)
- [Catalog](https://marketplace.visualstudio.com/VSCode)
- [Changelog](https://code.visualstudio.com/updates)
- [Blog](https://code.visualstudio.com/blogs)
- [Git Hub](https://github.com/microsoft/vscode)
- [Issue Tracker](https://github.com/microsoft/vscode/issues)
- [Community](https://code.visualstudio.com/community)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/visual-studio-code)
- [X (Twitter)](https://x.com/code)
- [LinkedIn](https://www.linkedin.com/showcase/microsoft-visual-studio-code)
- [YouTube](https://www.youtube.com/@code)
- [Terms of Service](https://marketplace.visualstudio.com/policies/agree)
- [Privacy Policy](https://privacy.microsoft.com/privacystatement)
