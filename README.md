# Invook AI Documentation

Documentation for Invook AI, a creative platform for generating images, videos, and text using a credit-based system on a shared Canvas.

## Overview

Invook provides a powerful shared Canvas and Drive where users can collaborate on AI-generated assets. Interactions are built around **Blocks** (formerly nodes) that can be connected to build complex creative workflows.

## Documentation Structure

- **Getting Started**: Learn the basics of the [Canvas](/support/canvas-overview) and [Toolbox](/support/toolbox).
- **Models**: Detailed credit costs for [Image](/models/image), [Video](/models/video), and [Text](/models/text) models.
- **Billing**: Understand [Membership Plans](/help/billing) and [Credit Add-ons](/help/billing#credit-add-ons).
- **Tutorials**: Step-by-step guides like [Create Your First Asset](/tutorial/create-first-asset).

## Development

This documentation is built on [Mintlify](https://mintlify.com).

### Prerequisites

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

### Local Preview

Run the following command at the root of the project:

```bash
mint dev
```

Preview locally at `http://localhost:3000`.

### Integrity Checks

Check for broken links:

```bash
mint broken-links
```

## Terminology

- **Block**: The fundamental element on the Canvas (input, model, prompt, etc.). Formerly referred to as "nodes" in early versions of the codebase and documentation.
