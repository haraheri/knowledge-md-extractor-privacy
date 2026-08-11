---
layout: privacy
title: Knowledge MD Extractor Privacy Policy
description: Privacy Policy for the Knowledge MD Extractor Chrome extension.
permalink: /privacy/
---

# Knowledge MD Extractor Privacy Policy

**Last updated: August 9, 2026**

## Overview

Knowledge MD Extractor has a single purpose: to extract the readable content of
the active web page into editable Markdown. Users can review and edit the
extracted Markdown, then copy or download it for their own notes,
documentation, or knowledge base.

## Data handled

When a user explicitly chooses Extract, Knowledge MD Extractor temporarily
handles website content from the currently active HTTP or HTTPS page. This may
include readable text, headings, lists, tables, code blocks, links, images,
page metadata, and the page URL.

Website content may itself contain names, contact details, or other personal
information. The developer does not receive, collect, or have access to that
content. The extension does not separately collect personally identifiable
information, health information, financial or payment information,
authentication information, personal communications, location, web history,
or user activity.

## Purpose of data use

Website content is used only to identify readable main content and convert it
into editable Markdown in the extension popup. It is not used for advertising,
profiling, creditworthiness, lending, or any purpose unrelated to this single
purpose.

## Local processing and data transmission

Extraction, sanitization, Markdown conversion, editing, and filename generation
run locally in Chrome. Knowledge MD Extractor does not transmit website
content, page metadata, extracted Markdown, or edits to the developer or any
external server.

The extension does not make external network requests and does not use
analytics, telemetry, advertising, tracking, or AI services.

## Data storage and retention

Knowledge MD Extractor does not persist website content or extracted Markdown
in extension storage. Extracted Markdown and edits remain in the popup only
while it is open and are discarded when the popup closes.

When the user chooses Copy, the edited Markdown is written to the device's
clipboard. When the user chooses Download, the edited Markdown is saved as a
local `.md` file on the user's device. These actions occur only at the user's
request and are controlled by the user and their device.

## Data sharing and selling

Knowledge MD Extractor does not sell, share, or transfer website content,
generated Markdown, metadata, or edits to third parties. It does not use or
transfer user data for purposes unrelated to the extension's single purpose or
for creditworthiness or lending purposes.

## Permissions

Knowledge MD Extractor requests only the following Chrome permissions:

- `activeTab`: Allows access to the currently active page only after the user
  explicitly invokes the extension. It avoids persistent access to websites.
- `scripting`: Allows the packaged extraction script to be injected into the
  active page when the user requests extraction. The extension does not use a
  persistent content script.
- `downloads`: Allows the edited Markdown to be saved as a local `.md` file only
  when the user chooses Download.

The extension has no host permissions or background service worker.

## Remote code

Knowledge MD Extractor does not load or execute JavaScript, WebAssembly, or
other executable code from remote servers. All executable code required by the
extension is included in the extension package.

## Contact

For privacy questions about Knowledge MD Extractor, contact
[yuto.otake.dev@gmail.com](mailto:yuto.otake.dev@gmail.com).
