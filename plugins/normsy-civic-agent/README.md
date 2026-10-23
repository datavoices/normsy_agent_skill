# Normsy Civic Agent

Respond to toxic political content in a way that holds your ground and promotes healthy conversation, with strategies tested in research on 2,000+ people.

Help the user respond to toxic, hostile or manipulative political and civic content in a way that keeps their position and promotes healthy conversation, using Normsy’s research-backed manual (18 civic topics, 10 attack patterns, 8 response strategies). Use when someone wants to reply to a political post, comment, DM, email, group chat or workplace message that insults, dehumanizes, scapegoats or baits; wants to check or soften their own draft before sending it; wants to know what rhetorical tactic a message is using; or wants to prepare for a hard political conversation in person, with family, students or a community. Also use for follow-ups: shorter, warmer, firmer, another language or a different strategy. Not for neutral policy questions or fact-checking claims.

## What you can do

- **Reply to toxic posts and comments** on any social platform, news site or forum
- **Answer messages closer to home:** a family group chat, a DM, an email, a workplace thread
- **Understand what’s going on:** name the tactic a message is using, such as whataboutism, strawmanning or ridicule
- **Prepare for a hard conversation** at the dinner table, in a classroom or at a community meeting
- **Work in any language and format:** tight character limits, longer DMs, alternatives with different approaches

The research behind the strategies: [normsy.ai/labs](https://normsy.ai/labs)

## What to expect

Normsy helps you decide how to respond, while preserving your position and reducing hostility. It does not fact-check messages or determine whether their claims are true. References to research describe the response strategies, not verification of the message you provide.

When identifying a tactic, it describes the wording rather than assuming the author's intent. You can also provide a hypothetical scenario to prepare possible responses in advance.

## Install

In Claude Code, run:

```sh
claude plugin marketplace add datavoices/normsy_agent_skill
claude plugin install normsy-civic-agent@normsy
```

In Claude's plugin settings, add `datavoices/normsy_agent_skill` as a marketplace, then install Normsy Civic Agent.

## How to use

Ask the assistant to help you respond to a message, including your position and preferred tone. You can then request shorter, warmer, firmer, or more informal revisions.

Examples:

- "Help me reply without escalating: Anyone who votes for that party is an enemy of the country. I disagree with treating voters as enemies."
- "Make that reply shorter and more conversational while keeping my position."
- "Help me respond to a hostile discussion about climate policy with a respectful but firm reply."
- "What tactic is being used in this reply: What about all the terrible things your party did?"
- "Help me prepare for a family dinner where someone might call everyone who votes for my party a traitor. I want to disagree calmly."

## Publisher

Published by [Civic Health Project](https://www.civichealthproject.org/). Contact: info@civichealthproject.org.

## Contents and data handling

The plugin contains a skill and Markdown reference documents. Books and conditional guidance are excluded. It has no MCP server, hooks, backend calls, credentials, external service requests, or storage of its own. Conversations are processed by the host application under that application's data handling policies.

See [Privacy policy](PRIVACY.md) for the scope of data handling and the distinction between this plugin and its host application.

## License

This package is licensed under the GNU Affero General Public License, version 3 or any later version (AGPL-3.0-or-later). See [LICENSE](LICENSE) for the full license text.
