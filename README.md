# MacVisor: issues and feature requests

MacVisor is made by [ScaleNinja](https://scaleninja.com).

This is the public place to report bugs, ask questions and suggest features for
**[MacVisor](https://scaleninja.com/macvisor/)**, a native virtual machine
manager for Apple Silicon. It runs macOS, Linux, Windows 11 (Tech Preview) and
FreeBSD (experimental) guests on Apple's Virtualization framework.

MacVisor's source code isn't public; this repository holds issues only.

- **Download and free 30-day trial:** https://scaleninja.com/macvisor/
- **Docs:** https://scaleninja.com/docs/macvisor/
- **Changelog:** https://scaleninja.com/docs/macvisor/changelog/
- **Troubleshooting:** https://scaleninja.com/docs/macvisor/troubleshooting/

## Before you open an issue

1. **Update MacVisor** (MacVisor → Check for Updates…). Your issue may already be fixed.
2. **Search the [existing issues](https://github.com/macvisor/macvisor/issues)**, open and closed. Add a 👍 or a comment to one that matches, rather than opening a duplicate.
3. **Check [Troubleshooting](https://scaleninja.com/docs/macvisor/troubleshooting/)** and [Known limitations](https://scaleninja.com/docs/macvisor/known-limitations/).

## Feature requests

Welcome! Tell us what you're trying to do, not only the feature you have in
mind: "I want my homelab VMs on their own VLAN" helps more than "add a VLAN
button". Upvote existing requests with 👍; we use them to decide what comes next.

## Reporting a bug

Please include:

- **MacVisor version and build**, from `MacVisor > About MacVisor`, e.g. 27.2.0 (50).
- **macOS version** and your **Mac model**, e.g. macOS 27.2, Mac mini M4.
- **The guest:** OS and version, and how it was made (cloud image, ISO, IPSW, template, import).
- **What you did, what you expected, and what happened.** Steps to reproduce help most.
- **The exact error message**, or a screenshot.
- **Logs, if you can:** choose **Help > Report a Problem** in MacVisor. It saves a zip of the logs and a summary. Attach it here only after checking it (see below), or email it to `support@scaleninja.com`
  and mention this issue's number.

## Please don't post here

- **License keys, order numbers or anything about payments, refunds or your account.**
  Email support@scaleninja.com instead.
- **Passwords, SSH keys, tokens or other secrets.** Check screenshots and logs
  before attaching them: logs can contain file paths, VM names and network addresses.
- **Security vulnerabilities.** Please report them privately to
  security@scaleninja.com, with "Security" in the subject, so we can fix them
  before they're public. See https://scaleninja.com/security/

## What to expect

MacVisor is made by a small independent team at ScaleNinja. We read every issue, but can't
promise a reply time. Bugs that lose data or block many people come first. Fixes
ship as MacVisor updates, and the changelog says what changed.

## Be kind

Be respectful and constructive. Issues are for MacVisor; general questions about
macOS, Apple's Virtualization framework or a guest OS are better asked elsewhere.
