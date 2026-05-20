# Plugin (plugin)
An index and topic collection covering plugin, extension, and add-on architectures with public APIs and marketplaces. This collection spans editor and IDE plugin ecosystems (VS Code Marketplace, JetBrains Marketplace, Chrome Web Store, Firefox Add-ons), SaaS platform extension marketplaces (Atlassian Marketplace and Forge, Salesforce AppExchange, Shopify App Store, WordPress Plugins, Slack Apps, Discord Apps, Microsoft AppSource, Google Workspace Marketplace, Notion, Postman, Figma, Sketch, Webflow Apps, HubSpot Marketplace, Zapier App Directory), API gateway plugin frameworks (Kong Plugin Hub, Tyk Plugins, Gravitee Plugins), identity extensibility (Auth0 Actions and Extensions), and AI plugin and tool ecosystems (Open WebUI Functions, ChatGPT Plugins and GPTs, Claude Code plugins, OpenAI tools).

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Plugin, Extension, Marketplace, App Directory, Add-on

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Plugin Manifest Schema](https://raw.githubusercontent.com/api-evangelist/plugin/refs/heads/main/json-schema/plugin-manifest-schema.json)
- [JSONSchema - Marketplace Listing Schema](https://raw.githubusercontent.com/api-evangelist/plugin/refs/heads/main/json-schema/plugin-marketplace-listing-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/plugin/refs/heads/main/json-ld/plugin-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/plugin/refs/heads/main/vocabulary/plugin-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Plugin Manifests | Marketplaces and runtimes use declarative manifests (manifest.json, plugin.xml, app manifests) to describe identity, permissions, entry points, and capabilities of a plugin. |
| Marketplace Listing and Discovery APIs | Public APIs and search endpoints expose listings, categories, ratings, and download counts so developers and users can discover plugins across major marketplaces. |
| Extension Points and Hooks | Host platforms expose well-defined extension points, events, and lifecycle hooks (Forge modules, Shopify Functions, Auth0 Actions, Kong plugin phases, WordPress hooks) that plugins implement. |
| Install, Update, and Entitlement Flows | Marketplaces standardize installation, OAuth grant, license check, and entitlement validation flows for individual users, organizations, and tenants. |
| Sandboxing and Permissions | Plugin runtimes enforce permission scopes, sandboxed execution, and review processes to protect host platforms and end users. |
| AI Tooling and Agent Plugins | AI platforms expose plugin and tool surfaces (ChatGPT GPTs, Open WebUI Functions, Claude Code plugins, OpenAI tools) that extend LLM behavior with custom actions. |
| API Gateway Plugin Frameworks | API gateways such as Kong, Tyk, and Gravitee define plugin frameworks where auth, transformation, rate limiting, and observability are distributed as installable plugins. |

## Use Cases

| Name | Description |
|------|-------------|
| Editor and IDE Extensibility | Ship language support, linters, debuggers, and AI assistants as plugins through VS Code Marketplace and JetBrains Marketplace. |
| SaaS Platform App Marketplaces | Build apps on Salesforce AppExchange, Shopify App Store, Atlassian Marketplace, HubSpot Marketplace, and Slack App Directory to extend SaaS platforms. |
| Browser Extension Distribution | Package and distribute browser extensions for content blocking, productivity, and accessibility through Chrome Web Store and Firefox Add-ons. |
| API Gateway Customization | Extend Kong, Tyk, and Gravitee with custom plugins for authentication, request transformation, and policy enforcement. |
| CMS and Commerce Extensibility | WordPress plugin directory and Shopify App Store extend CMS and commerce platforms with payment processors, shipping, and analytics. |
| AI Agent Tooling | Publish ChatGPT GPTs and plugins, Open WebUI Functions, and Claude Code plugins to give AI agents domain-specific tools and connectors. |
| Identity and Access Extensions | Auth0 Actions, Extensions, and Marketplace add custom rules, MFA providers, and SSO integrations to identity flows without forking the platform. |

## Integrations

| Name | Description |
|------|-------------|
| VS Code Marketplace | Microsoft's marketplace for Visual Studio Code and Visual Studio extensions, with a Gallery API for search, download, and metadata. |
| JetBrains Marketplace | Official plugin and theme distribution platform for IntelliJ IDEA, PyCharm, WebStorm, and other JetBrains IDEs with a public plugins API. |
| Chrome Web Store | Google's distribution channel for Chrome and Edge browser extensions and themes, governed by Manifest V3 and the Chrome Web Store API. |
| Atlassian Marketplace | Marketplace for apps extending Jira, Confluence, and Bitbucket, including Atlassian Connect and Forge apps with a public Marketplace REST API. |
| Salesforce AppExchange | Enterprise marketplace for managed packages and Lightning components extending Salesforce CRM, with package install APIs and security review. |
| Shopify App Store | Marketplace for apps extending Shopify Admin, Storefront, and Checkout via Shopify Apps, Functions, and Theme App Extensions. |
| WordPress Plugin Directory | Open directory of free WordPress plugins powering a large share of the web, distributed through wordpress.org with a public plugins.org API. |
| Slack App Directory | Directory of Slack apps and integrations built on the Slack platform, manifested through app config and the Apps API. |
| Microsoft AppSource | Microsoft's marketplace for business apps and Office 365 add-ins, Teams apps, and Power Platform connectors. |
| Google Workspace Marketplace | Distribution platform for Google Workspace add-ons and Apps Script-based extensions to Gmail, Drive, Docs, Sheets, and Calendar. |
| HubSpot Marketplace | Marketplace for HubSpot apps, themes, and templates extending the HubSpot CRM and CMS via OAuth apps and serverless functions. |
| Zapier App Directory | Directory of integrations and triggers/actions that Zapier exposes to its automation builder via the Zapier Platform CLI. |
| Kong Plugin Hub | Catalog of first-party and community plugins for Kong Gateway and Konnect, written in Lua, Go, or JavaScript. |
| Open WebUI Functions | Pluggable functions, tools, and pipelines that extend the Open WebUI LLM chat interface with custom integrations. |

## Artifacts

Machine-readable specifications organized by format.

### JSON Schema

- [Plugin Manifest Schema](json-schema/plugin-manifest-schema.json)
- [Marketplace Listing Schema](json-schema/plugin-marketplace-listing-schema.json)

### JSON Structure

- [Plugin Manifest Structure](json-structure/plugin-manifest-structure.json)
- [Marketplace Listing Structure](json-structure/plugin-marketplace-listing-structure.json)

### JSON-LD

- [Plugin Context](json-ld/plugin-context.jsonld)

## Vocabulary

- [Plugin Vocabulary](vocabulary/plugin-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across plugin manifests, marketplace listings, installs, and extension points

## Network

This index references the following plugin and extension marketplace repositories:

- [VS Code Marketplace](https://github.com/api-evangelist/vs-code-marketplace)
- [JetBrains Marketplace](https://github.com/api-evangelist/jetbrains-plugin)
- [Google Chrome](https://github.com/api-evangelist/google-chrome)
- [Atlassian](https://github.com/api-evangelist/atlassian)
- [Salesforce](https://github.com/api-evangelist/salesforce)
- [Shopify](https://github.com/api-evangelist/shopify)
- [WordPress](https://github.com/api-evangelist/wordpress)
- [Slack](https://github.com/api-evangelist/slack)
- [Discord](https://github.com/api-evangelist/discord)
- [Microsoft Office 365](https://github.com/api-evangelist/microsoft-office-365)
- [Google Workspace](https://github.com/api-evangelist/google-workspace)
- [Notion](https://github.com/api-evangelist/notion)
- [Postman](https://github.com/api-evangelist/postman)
- [Figma](https://github.com/api-evangelist/figma)
- [Webflow](https://github.com/api-evangelist/webflow)
- [HubSpot](https://github.com/api-evangelist/hubspot)
- [Zapier](https://github.com/api-evangelist/zapier)
- [Auth0](https://github.com/api-evangelist/auth0)
- [Kong](https://github.com/api-evangelist/kong)
- [Tyk](https://github.com/api-evangelist/tyk)
- [Gravitee](https://github.com/api-evangelist/gravitee)
- [Open WebUI](https://github.com/api-evangelist/open-webui)
- [ChatGPT](https://github.com/api-evangelist/chatgpt)
- [OpenAI](https://github.com/api-evangelist/openai)
- [Claude](https://github.com/api-evangelist/claude)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
