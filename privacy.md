---
layout: default
title: Privacy policy — ghostlyyy Design Library
---

# Privacy policy

Last updated: September 16, 2026

## Operator and scope

ghostlyyy operates ghostlyyy Design Library, a personal design-reference tool currently in development. This notice describes the informational website and the proposed connector. It does not represent the privacy policies of Pinterest, OpenAI or GitHub.

**Contact:** Open an issue in the [ghostlyyy Design Library repository](https://github.com/rhen-bot/design-library/issues). Issues are public; include only the information needed to describe your inquiry. For a request involving private information, ask for a private follow-up channel without posting that information.

## Current website

The informational website has no app sign-up form, upload form, Pinterest login flow, advertising or application analytics scripts. The connector is not operational and is not currently collecting Pinterest account data.

The intended website host is GitHub Pages. GitHub may process technical information associated with visits under its own [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Information voluntarily sent to the operator through the published contact channel is used to respond to that inquiry.

## Proposed connector data and purpose

Subject to API approval and the user's authorization, the planned local connector would access the connected account's identity and authorized public Pin and Board information. This may include identifiers, descriptions, source links, images and available animation frames. It would use that information to find and inspect the user's visual references for design tasks.

The initial release is intended for the operator's own use. Secret Boards, advertising management and writing to Pinterest are outside that release's scope. Pinterest authentication would use OAuth; the connector would not ask for a Pinterest password or browser-session cookies.

The user could also provide design preferences and appropriately permitted local reference files. Explicit preferences would help guide later design tasks.

## AI processing and other providers

The proposed creative workflow involves OpenAI's Codex and potentially its image-generation tools. Selected reference content and task instructions may therefore leave the local device and be processed by those services. Calling the connector local does not mean the entire creative workflow runs locally.

Pinterest-derived content will not be sent for this processing unless its use is permitted. The project does not itself train or fine-tune AI models. Provider retention and model-improvement settings are separate from this project and depend on the service and account used; this notice does not promise zero retention or make claims about those settings.

The operator does not sell personal data. This project is not designed to use account information for advertising.

## Planned storage and retention

The planned connector would keep authorization credentials in protected local storage and retain them only while the account remains connected. Credentials would not be included in reference results, public site files or application logs.

The plan does not assume permission to maintain a permanent Pinterest archive. Persistent copies of API content, derived summaries or embeddings would require an established permission basis. Any temporary processing, caching and deletion behavior must be specified and tested before the integration is enabled.

User-authored preferences, permitted local reference files and generated work may be saved locally until the user removes them. Copies of reference content or outputs in Codex conversations, provider systems or user-managed backups are subject to those systems' separate controls.

## Access, removal and inquiries

Once OAuth is available, the user would be able to revoke the app's Pinterest access and disconnect the local connector. The implementation must support removal of its locally stored credentials and preferences. Revoking access does not itself delete content already present in a separate AI conversation or an exported file.

Privacy questions or requests concerning information held by the operator should be sent through the contact above. Please do not include passwords, tokens or private reference files in a public GitHub issue.

## Changes before launch

This notice will be updated to describe the implemented data flows, enabled providers, retention periods and deletion controls before live processing begins or access is shared with other users. Material changes will be reflected on this page with a new update date.

[About Design Library](index.html)
