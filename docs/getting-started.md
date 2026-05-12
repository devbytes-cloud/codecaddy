# Getting started with CodeCaddy

Welcome. This guide walks through your first 5 minutes with CodeCaddy, enough to save your first snippet, find it later, and share it with a teammate.

## 1. Sign in (or don't)

Go to [app.codecaddy.dev](https://app.codecaddy.dev). You can start saving snippets locally without an account; they'll live in your browser. Sign in with GitHub or Google when you want cloud sync across devices.

## 2. Save your first snippet

Click **New snippet** in the top-right. Paste anything: a kubectl command, a Helm value override, a Terraform module call. Give it a title that describes what it does, not what it is. ("Force-delete stuck namespace" beats "kubectl delete ns".)

Tag it. Tags are your primary way to find snippets later, so use them generously: `kubectl`, `helm`, `prod`, `incident-response`. Multiple tags per snippet are encouraged.

Hit **Save**. CodeCaddy creates a revision automatically; every save is versioned from this point forward.

## 3. Find it later

CodeCaddy has a **Tags** dropdown for filtering your snippets. Type or scroll to pick a tag, and the view filters to matching snippets. You can also filter by **Source** (All, Local, or Cloud) to scope your view to just one storage location.

This is why tagging matters. A `kubectl` tag finds every kubectl snippet you've ever saved; an `incident-response` tag pulls up the runbook fragments you wrote at 3am six months ago. Untagged snippets are still saved, but they're hard to find later, so tag generously.

## 4. Update it (without losing the original)

Open the snippet, edit it, hit Save. The old version is preserved as a revision. Click **History** to see all revisions and diff between any two.

This is where CodeCaddy differs from a notes app: every save is a checkpoint. You can always go back.

## 5. Share it

Click **Share** on any snippet. CodeCaddy generates a time-limited share link (default: 24 hours, configurable up to 30 days). Send it to a teammate via Slack, email, whatever.

Share links are read-only. The recipient can view and copy; they can't edit your snippet.

## What's next

- [FAQ](faq.md) for common questions
- [Discussions](https://github.com/devbytes-cloud/codecaddy/discussions) for everything else
- Upgrade to Pro ($5/mo, [details](https://codecaddy.dev#pricing)) for cloud sync and longer share link expiration

That's it. No setup, no config files, no plugins. Save things; find them later.
