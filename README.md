# Yigit Mert Atalay

I work in marketing operations and data in Vancouver, Canada. My background is performance marketing, and these days I mostly build the systems behind marketing: conversion tracking, a marketing data warehouse, and AI agents that run inside real workflows with a person approving what matters.

**What I work with**

- **Tracking and attribution:** GA4, Google Tag Manager, Google Ads and Meta conversions, CRM integrations, WordPress plugins
- **Data:** BigQuery, Dataform, SQL, Python
- **AI in workflows:** agents and chatbots with evaluation sets and human approval, MCP tools
- **Web:** TypeScript, Astro, Next.js, WordPress and PHP

Most of my work code lives in private repositories. Case studies are on **[mertatalay.com](https://mertatalay.com)**.

## AdaletAI

[AdaletAI](https://github.com/mert-atalay/adaletai) is my own project: a legal-work assistant for Turkish lawyers. It answers from a matter's documents and from legal sources, cites the exact passage behind every claim, and turns the conversation into a draft for a lawyer to review. Next.js, TypeScript, Supabase, hybrid retrieval, and evaluation suites that run with the build. The source is private; the linked page describes how it is built and what it does not do yet.

## Marketing and data projects

These are small, working examples of how I build things. They run on synthetic data or test fixtures, each has tests that run on every change, and each README lists what it does not do.

| Project | What it is |
| --- | --- |
| [audience-to-creative](https://github.com/mert-atalay/audience-to-creative) | A pipeline from audience intelligence to ranked creative briefs to generated ad creative. Every insight traces back to its data, every variant passes brand and claims checks, a person approves, and results feed the next round. Python. |
| [marketing-warehouse-starter](https://github.com/mert-atalay/marketing-warehouse-starter) | A starter marketing data warehouse: Dataform models for BigQuery that are tested locally on DuckDB, with checks that report totals match the raw data. |
| [marketing-analyst-mcp](https://github.com/mert-atalay/marketing-analyst-mcp) | An MCP server that lets an AI assistant answer marketing questions from governed metrics instead of free SQL, with an evaluation set and human approval for budget changes. TypeScript. |
| [wp-conversion-tracking](https://github.com/mert-atalay/wp-conversion-tracking) | A reference WordPress plugin that keeps a lead's traffic source, attaches it to form submissions and sends one de-duplicated conversion event after consent. PHP. |
| [wordpress-content-mcp](https://github.com/mert-atalay/wordpress-content-mcp) | An MCP server that lets an AI assistant read and audit a WordPress site and propose changes as drafts only, so a person publishes. TypeScript. |
| [local-presence-audit](https://github.com/mert-atalay/local-presence-audit) | A free command-line audit of a business's public Google Maps listing: completeness, reviews, hours, website consistency and nearby competitors. TypeScript. |
| [BrandSafe](https://github.com/mert-atalay/brandsafe) | An earlier side project on brand-safe ad creative: the AI generates only the background, and ordinary code places the logo and text so they are never redrawn. FastAPI, Next.js, Supabase. |

## Games I made for my daughter

| Project | What it is |
| --- | --- |
| [Uzay](https://github.com/mert-atalay/uzay) | A true-scale space game. The real Solar System at 1:1, about 15,000 real stars and a ray-traced black hole. Godot 4, with tests and automated builds. |
| [Toddler Island](https://github.com/mert-atalay/toddler-island) | A gentle 3D world for a two-year-old: a farm, a safari, a treehouse, around 35 animals to feed and a trip to the Moon. Godot 4. |
