# Frequently Asked Questions

## How is CodeCaddy different from GitHub Gists?

GitHub Gists are great for sharing public code. CodeCaddy is built for the private command-line knowledge you accumulate
doing infra work: kubectl commands, Helm overrides, sequence-of-steps for incident response. Snippets are private by
default, version-controlled per snippet, and shared through time-limited links instead of all-or-nothing public posts.

## How is it different from a code editor's snippets feature?

VS Code snippets are tied to one editor on one machine. CodeCaddy is web-based and works from any browser. If you sign
in and use cloud sync, your snippets follow you between work laptop, personal machine, and any other device you log
into. It also has revision history, which most editor snippet systems don't.

## Where is my data stored?

It depends on whether you sign in.

**Local snippets** (no account, or signed-in but saved locally) live in your browser's local storage on your device. They never leave that browser. They aren't sent to our servers, aren't backed up by us, and aren't accessible from any other device.

**Cloud snippets** (saved while signed in with cloud sync) are stored in our cloud database, encrypted at rest with AES-256, and synced across any device where you're signed in.

For the full list of infrastructure providers we use, see our [Privacy Policy](https://codecaddy.dev/privacy).

## Can I use CodeCaddy without an account?

Yes. You need network access to load codecaddy.dev, but once it's loaded, you can save snippets locally without signing
in. Those snippets stay in your browser on that one device.

Sign in (with GitHub or Google) when you want cloud sync across devices.

## What's the difference between local and cloud snippets?

|                                     | Local                        | Cloud                                        |
|-------------------------------------|------------------------------|----------------------------------------------|
| Account required                    | No                           | Yes                                          |
| Storage location                    | Your browser's local storage | Our cloud database (Neon, AES-256 encrypted) |
| Synced across devices               | No                           | Yes                                          |
| Available if you clear browser data | No (gone)                    | Yes                                          |
| Backed up by us                     | No                           | Yes                                          |
| Visible to DevBytes operators       | No                           | Only as needed to operate the service        |

You can mix both. Save sensitive credentials locally, sync your everyday infra snippets to the cloud, or do whatever
combination fits your trust model.

## What languages does CodeCaddy support?

We support syntax highlighting for a wide range of languages, including the ones platform engineers actually use day-to-day: Bash, YAML, Dockerfile, Go, Python, Rust, TypeScript, SQL, JSON, and more. If you don't see one you need, [open a Discussion](https://github.com/devbytes-cloud/codecaddy/discussions/categories/ideas) and we'll take a look.

## Can I export my snippets?

Export is on the roadmap but not available yet. Your data is never locked in: if you need to migrate before we ship
export, [open a Discussion](https://github.com/devbytes-cloud/codecaddy/discussions) and we'll help you get your data
out.

## Can I self-host CodeCaddy?

Not today. CodeCaddy is hosted SaaS. We may consider self-hosted options for teams later, but it's not on the immediate
roadmap.

## Is there a free tier?

Yes. The free tier includes local snippet storage in your browser. Pro ($5/mo or $45/yr) adds cloud sync across devices,
longer share link expiration, and priority bug fixes. [See pricing](https://codecaddy.dev#pricing).

## How do I cancel or manage my subscription?

Subscription management is handled through [Polar](https://polar.sh), our payment processor. When you subscribed, Polar
sent you an email with a link to your customer portal; that's where you cancel, update your payment method, or view
invoices. If you've lost the email, check your inbox for "Polar" or email support@codecaddy.dev and we'll resend the
link.

Cancellation takes effect at the end of your current billing period; you keep paid features until that date and revert
to free after. No refunds, but no surprise charges either. See [Terms](https://codecaddy.dev/terms) Section 8.

## Do you train AI on my snippets?

No. We don't read, analyze, or train AI on the contents of your snippets. We process them only to provide the service to
you. See [Privacy Policy](https://codecaddy.dev/privacy) Section II for the explicit commitment.

## How do I report a security issue?

Email **security@codecaddy.dev**. See [SECURITY.md](../SECURITY.md) for full details on our security policy and
disclosure process.

## How do I contact support?

For billing or account issues: support@codecaddy.dev. For general
questions: [GitHub Discussions](https://github.com/devbytes-cloud/codecaddy/discussions). For
bugs: [GitHub Issues](https://github.com/devbytes-cloud/codecaddy/issues).
