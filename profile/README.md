# MailChannels developer resources

Build transactional email into your server-side applications with the [MailChannels Email API](https://docs.mailchannels.com/email-api/overview).

## Official SDKs

| Language | Install | Quickstart | Source |
| --- | --- | --- | --- |
| JavaScript / TypeScript | [`mailchannels-sdk` on npm](https://www.npmjs.com/package/mailchannels-sdk) | [Node.js quickstart](https://docs.mailchannels.com/email-api/javascript/quickstart) | [Bitbucket](https://bitbucket.org/mailchannels/mailchannels-email-api-sdk-js) · [GitHub mirror](https://github.com/mailchannels/mailchannels-email-api-sdk-js) |
| Python | [`mailchannels` on PyPI](https://pypi.org/project/mailchannels/) | [Python quickstart](https://docs.mailchannels.com/email-api/python/quickstart) | [Bitbucket](https://bitbucket.org/mailchannels/mailchannels-email-api-sdk-py) · [GitHub mirror](https://github.com/mailchannels/mailchannels-email-api-sdk-py) |
| PHP | [`mailchannels/mailchannels-php` on Packagist](https://packagist.org/packages/mailchannels/mailchannels-php) | [PHP quickstart](https://docs.mailchannels.com/email-api/php/quickstart) | [Bitbucket](https://bitbucket.org/mailchannels/mailchannels-email-api-sdk-php) · [GitHub mirror](https://github.com/mailchannels/mailchannels-email-api-sdk-php) |

The canonical SDK source repositories are hosted on Bitbucket; the GitHub mirrors sync daily for discovery and browsing. Use the canonical repositories for development and contribution instructions. Install released packages from the registries linked above.

## Frameworks and agent skills

- [Laravel Mail integration](https://docs.mailchannels.com/email-api/laravel)
- [Symfony Mailer integration](https://docs.mailchannels.com/email-api/symfony)
- [MailChannels skills for Codex](https://github.com/mailchannels/mailchannels-codex-plugin)
- [MailChannels skills for Claude Code](https://github.com/mailchannels/mailchannels-claude-code-plugin)

The agent repositories include installation instructions and guidance for evaluating, implementing and operating Email API applications.

## Workflow automation

Use the [MailChannels integration on Zapier](https://zapier.com/apps/mailchannels/integrations) to send transactional email from other applications. Published templates include [Google Forms confirmations](https://zapier.com/apps/google-forms/integrations/mailchannels/255731698/send-mailchannels-confirmation-emails-for-new-google-forms-responses) and [Stripe subscription welcome emails](https://zapier.com/apps/mailchannels/integrations/stripe/255731696/send-welcome-emails-through-mailchannels-for-new-stripe-subscriptions).

## Hosting providers

[MailChannels Email API for WHMCS](https://docs.mailchannels.com/plugins/whmcs/overview) lets hosting providers sell Email API sub-accounts from their WHMCS stores. WHMCS handles billing while the plugin provisions sub-accounts, send limits, and API or SMTP credentials. See the [installation guide](https://docs.mailchannels.com/plugins/whmcs/installation) and [official source](https://bitbucket.org/mailchannels/mailchannels-email-api-whmcs-plugin).

## Development previews

These candidates are available for evaluation from source. They are not yet released to npm, PyPI or RubyGems, or published in their target integration catalogs. Check each repository's validation and release requirements before use.

| Integration | Purpose | Source and issue tracking |
| --- | --- | --- |
| Ruby | Direct Email API sending and dry-run validation; not an Action Mailer backend | [Ruby client](https://github.com/mailchannels/mailchannels-email-api-ruby) |
| Node-RED | Send or validate transactional email from a flow, with dry-run enabled by default | [Node-RED node](https://github.com/mailchannels/node-red-mailchannels) |
| Directus | Sandboxed Flow operation for the Email API send payload | [Directus extension](https://github.com/mailchannels/directus-extension-mailchannels) |
| LangChain | Email tool with an application-controlled sender and recipient allowlist | [LangChain integration](https://github.com/mailchannels/langchain-mailchannels) |

## Get started and get help

- [Create an account](https://dash.mailchannels.com)
- [Send your first email with cURL](https://docs.mailchannels.com/email-api/curl/quickstart)
- [API reference](https://docs.mailchannels.com/email-api/api-reference-introduction)
- [OpenAPI definition](https://docs.mailchannels.com/email-api.yaml)
- [MailChannels support](https://support.mailchannels.com/hc/en-us)

Follow the quickstart's account and sending-domain setup before sending. Keep API credentials in trusted server-side configuration.
