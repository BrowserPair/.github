<p align="center"><img src="https://browserpair.com/mark.svg" width="72" alt="BrowserPair logo"></p>

# BrowserPair

**Your AI agent. Your browser. Your rules.**

Connect ChatGPT, Claude, or your own AI agent to the Chrome profile you already use. BrowserPair combines scoped browser access, human approvals, durable tasks and verified outcomes through Remote MCP and REST.

[Website](https://browserpair.com) · [Start free](https://app.browserpair.com/) · [Documentation](https://docs.browserpair.com/) · [Chrome extension](https://chromewebstore.google.com/detail/agdomhjeahcbelohnmjmbldeldclnoof)

## Start here

| Resource | What you will find |
| --- | --- |
| [Product hub](https://github.com/BrowserPair/browserpair) | Setup, use cases, product questions and community |
| [Documentation](https://docs.browserpair.com/) | Quickstart, permissions, MCP and REST reference |
| [Examples](https://github.com/BrowserPair/examples) | Small REST examples and MCP connection recipes |
| [Skills](https://github.com/BrowserPair/skills) | Reusable workflows with clear inputs, boundaries and verification |
| [Awesome browser agents](https://github.com/BrowserPair/awesome-browser-agents) | A curated browser-agent ecosystem guide, including alternatives |

Current extension version: **0.4.0**.

## How it works

1. Pair your Chrome profile with BrowserPair.
2. Choose the browser, task intent and Standard or Developer mode.
3. Connect an external agent through MCP/REST, or configure your own model in the app.
4. Review approvals when needed and verify the result on the page.

Signed-in sessions stay in your Chrome profile. Task observations may reach your connected model; see [Security](https://browserpair.com/security) and [Privacy](https://browserpair.com/privacy).

This organization hosts public documentation and community resources. The BrowserPair application source is maintained separately and is private.

[Changelog](https://browserpair.com/changelog/) · [Status](https://status.browserpair.com/) · [Support](https://browserpair.com/support)

## Permission modes

Both modes work on every website and offer every browser tool. Standard asks only before payments and purchases, sign-in, account or security changes, deleting, sending or publishing, file uploads or downloads, and passwords or secrets. Developer has no mode confirmations. Task-requested confirmations and Chrome site permissions still apply; Chrome may ask you to grant site access.

Sign in with Google, GitHub or email/password. Remote MCP: `https://mcp.browserpair.com`; REST: `https://api.browserpair.com`.

Agents can observe the whole page and search captured full-page text. Outcomes are verified on the page, and uncertain steps are never repeated automatically.
