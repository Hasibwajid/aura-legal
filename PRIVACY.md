---
title: AURA Privacy Policy
---

# AURA Privacy Policy

_Last updated: 2026-09-02_

AURA is a small social app that helps you capture one visual moment a day and share it with a private circle of friends. This page explains what we collect, why, and what control you have over your data.

## What we collect

When you use AURA, we collect the minimum data needed to run the app:

- **Account**: your email address (used only for sign-in) and, once you set one, a hashed password.
- **Profile**: your display name, unique username, and optional profile photo.
- **Aura posts**: the photo you attach to each daily aura, the AI-generated mood word, description, and color it produced, and the date.
- **Friend graph**: friend requests, accepted friendships, and any blocks you create.
- **Reactions and pings**: emoji reactions you send on friend auras, and "ping" nudges when a friend hasn't posted yet.
- **Reports**: content or account reports you submit against other users.
- **Device diagnostics** (only if you opt in): anonymized crash reports and performance traces via Sentry, containing no personal messages or photos.

We do **not** collect location, contacts, advertising IDs, or third-party analytics identifiers.

## How we use it

- To sign you in and keep your session across app restarts.
- To render your daily aura and store your history so you and your accepted friends can revisit it.
- To share your aura only with users you have explicitly accepted as friends.
- To let you react, ping, block, or report other users.
- To detect and prevent abuse via the reports queue.

Photos you post are analyzed by our third-party AI provider (Groq) purely to generate the mood word, description, and color. The image is transmitted for analysis; we do not retain a separate copy at Groq, and the result is stored in your own Supabase row.

## Who can see your data

- **Your profile** (username, display name, avatar) is visible to any signed-in AURA user.
- **Your auras** are visible only to friends you have accepted, and to yourself.
- **Reactions** are visible to the aura's author and other friends of that author.
- **Reports and blocks** are visible only to you (and to AURA moderation when reviewing abuse).

## Where your data lives

Your data is hosted on **Supabase** (Postgres and Storage buckets on their managed infrastructure). Supabase's own privacy policy covers their handling: https://supabase.com/privacy

## Your controls

- **Change your profile photo**, display name, or username anytime from the Profile tab.
- **Delete any aura you posted** from that aura's detail page.
- **Block a user** from their friend aura page — they will no longer see your account.
- **Sign out** with "Switch account" on the Profile tab; your session ends until you sign in again.
- **Delete your entire account** with "Delete account" on the Profile tab. This permanently deletes:
  - your profile row and all aura posts,
  - your photos in Supabase Storage,
  - your reactions, pings, friendships, blocks, and reports,
  - your authentication record.

  Deletion is immediate and irreversible.

## Data retention

- Active accounts: we keep your data as long as your account exists.
- Deleted accounts: all rows and files listed above are removed within minutes of the deletion request completing.
- Report records may be retained in an anonymized form for abuse-prevention.

## Children

AURA is not intended for users under 13. If we learn we have inadvertently collected data from a child under 13, we will delete it promptly.

## Contact

Questions or requests about your data: **hello@aura.example.com** _(replace with your real address)_.

## Changes

If we materially change this policy, we will update the "Last updated" date at the top and, where practical, surface a notice in the app.
