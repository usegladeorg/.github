<p align="center">
  <img src="https://useglade.org/images/og.jpg" alt="Glade: private banking for people and the agents they run" width="100%">
</p>

<p align="center">
  <a href="https://useglade.org">Website</a> &nbsp;·&nbsp;
  <a href="https://docs.useglade.org">Docs</a> &nbsp;·&nbsp;
  <a href="https://x.com/usegladeorg">X</a> &nbsp;·&nbsp;
  <a href="mailto:contact@useglade.org">Email</a>
</p>

## Hi, we're Glade 👋

We're building a private bank on Robinhood Chain for people and for the AI agents that work on their behalf.

The idea is simple. When you send money with Glade, the payment is recorded on-chain like any other, so anyone can check that it happened. What they can't see is the amount. That stays encrypted, and only you and the person you paid can read it. Your keys never leave your device, and we never hold your funds.

Agents get the same treatment. Each one has its own account and a budget you set, and the rules live on-chain, so an agent physically can't spend more than you allowed. It can pay for an API call over x402, settle in about a tenth of a second, and carry on with its work without waking you up.

A glade is an open clearing in a forest. That's the feeling we're after: everything out in the open, and still a calm, private place to be.

## What's here

| Repository | About |
| --- | --- |
| [**glade-frontend**](https://github.com/usegladeorg/glade-frontend) | The website and the Glade app, built with Next.js and Supabase. Accounts, payments, cards, agent accounts and the developer settings all live here. |
| [**glade-smart-contracts**](https://github.com/usegladeorg/glade-smart-contracts) | The protocol itself, written in Solidity with Foundry. Encrypted USDG balances, the account registry behind `.glade` handles, agent spending rules, request-to-pay and fees. |
| [**glade-documentation**](https://github.com/usegladeorg/glade-documentation) | Everything you read on [docs.useglade.org](https://docs.useglade.org), from how one payment travels to how we think about security. |

## A few things we care about

**Privacy is the default.** You shouldn't have to opt in to keeping your finances to yourself.

**Your keys, your money.** Glade is non-custodial. If we disappeared tomorrow, your funds would still be yours.

**Rules that can't be talked around.** Agent limits are enforced by the chain, not by a server we promise to run carefully.

**Open where it counts.** The smart contracts are MIT licensed, and our fees are written into code anyone can read.

## Getting involved

Found a bug or have an idea? Open an issue in the relevant repo. For anything bigger than a small fix, it helps to start a conversation in an issue before sending a pull request, so we can agree on the approach first.

If you think you've found a security problem, please don't post it publicly. Email [contact@useglade.org](mailto:contact@useglade.org) instead and we'll work through it with you.

## Stay in touch

- Product and sign-up: [useglade.org](https://useglade.org)
- Documentation: [docs.useglade.org](https://docs.useglade.org)
- News and updates: [@usegladeorg](https://x.com/usegladeorg)
- Everything else: [contact@useglade.org](mailto:contact@useglade.org)
