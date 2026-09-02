---
title: AURA Privacy Policy
---

# AURA Privacy Policy

_Last updated: 2026-09-02_ · Contact: **lead2ai.ops@gmail.com**

AURA is a small social app that helps you capture one visual moment a day and share it with a private circle of friends. This page explains what we collect, why, and what control you have over your data.

## Delete your AURA account

You can permanently delete your AURA account in either of these ways.

### From the AURA app

1. Open AURA.
2. Select **Profile**.
3. Select **Delete account**.
4. Confirm permanent deletion.

### Without access to the app

Email **lead2ai.ops@gmail.com** from the email address connected to your AURA account.

Use the subject: **Delete my AURA account**

Include your AURA username in the message. We may ask you to verify ownership before completing the request.

### What is deleted

Deleting your account removes:

- your AURA authentication account,
- email address and profile,
- username and profile photo,
- verified phone number, if provided,
- contact-discovery identifiers derived from your own verified email or phone number,
- Aura posts and generated Aura information,
- uploaded photos,
- friendships and friend requests,
- reactions, pings, blocks, and reports linked to your account,
- any other account-linked activity stored by AURA.

Deletion is permanent and cannot be undone.

### Retention window

Account data is removed from AURA's active systems immediately after the deletion request is verified and processed. Data in encrypted infrastructure backups may remain for up to 30 days before automatically expiring. Anonymized records that can no longer identify you may be retained for abuse-prevention.

## What we collect

When you use AURA, we collect the minimum data needed to run the app:

- **Account**: your email address, used with a one-time verification code sent to that address. If you choose to set one, we also let our authentication provider store a hashed password so you can sign in without waiting for a code.
- **Profile**: your display name, unique username, and optional profile photo.
- **Phone number** (optional): if you choose to verify a phone number, we let our authentication provider store it so you can sign in via SMS and so friends can find you by that number through contact discovery. You can skip this entirely.
- **Contact-discovery identifiers** (only when you tap "Find from contacts"): salted server-side hashes of the email addresses and phone numbers you elect to submit for matching. See the Contact discovery section below.
- **Aura posts**: the photo you attach to each daily aura, the AI-generated mood word, description, and color it produced, and the date.
- **Friend graph**: friend requests, accepted friendships, and any blocks you create.
- **Social signals**: emoji reactions you send on friend auras, "ping" nudges when a friend hasn't posted yet, and content or account reports you submit.

We do **not** collect location, advertising IDs, or third-party analytics identifiers. We do **not** upload your contacts list; see the Contact discovery section for exactly what happens when you tap that feature.

## Contact discovery

AURA can optionally help you find friends from your device contacts. Contact email addresses and phone numbers are read only after you choose **Find from contacts**. Raw contact details and contact names are not stored. Identifiers are transmitted securely for temporary matching against users who have explicitly enabled discoverability. AURA stores only protected server-generated identifiers for your own verified email address or phone number. Contact names remain on your device. You can disable contact discoverability at any time.

Concretely:

- The device grants read-only access to contacts. AURA never writes to your contacts.
- Only the email addresses and phone numbers you elect to submit are transmitted to a server function; other contact fields (name, notes, photo, address) stay on-device.
- The server function computes a salted hash of each identifier, matches those hashes against the hashes of users who have opted into being discoverable, and returns only the AURA profile IDs of matches.
- The raw email addresses and phone numbers your device sent are discarded once matching completes.
- Contact discovery excludes users you have blocked and excludes your own account.
- Discoverability is opt-in per user. If you never enable "Let friends find me by email/phone," your identifiers are not stored on our servers for anyone else's matching.

## How we use it

- To sign you in and keep your session across app restarts.
- To render your daily aura and store your history so you and your accepted friends can revisit it.
- To share your aura only with users you have explicitly accepted as friends.
- To let you react, ping, block, or report other users.
- To match device contacts to existing AURA users, only when you initiate contact discovery.
- To detect and prevent abuse via the reports queue.

Photos you post are sent to our third-party AI provider (Groq) to generate the mood word, description, and color. Handling of that image at Groq is governed by their terms and privacy policy: https://groq.com/privacy-policy/. The generated result is stored in your own account row on our servers.

SMS delivery, when you opt into phone verification, is handled by the SMS provider configured in Supabase Authentication. The provider will be disclosed here once one is configured.

## Who can see your data

- **Your profile** (username, display name, avatar) is visible to any signed-in AURA user.
- **Your auras** are visible only to friends you have accepted, and to yourself.
- **Reactions** on an aura are visible to the aura's author and other accepted friends of that author.
- **Reports and blocks** are visible only to you (and to AURA moderation when reviewing abuse).
- **Your verified email or phone number** is discoverable through contact matching only if you enable that setting; otherwise those identifiers are not exposed to other users.

## Where your data lives

Your data is hosted on **Supabase** (Postgres and Storage on their managed infrastructure). Supabase's privacy policy covers their handling: https://supabase.com/privacy

## Your controls

- **Change your profile photo**, display name, or username anytime from the Profile tab.
- **Delete any aura you posted** from that aura's detail page.
- **Block a user** from their friend aura page — they will no longer see your account.
- **Disable contact discoverability** so your verified email or phone number cannot match anyone else's contacts. You can toggle this at any time in the Profile tab.
- **Revoke the contacts permission** in your device system settings at any time.
- **Sign out** with "Switch account" on the Profile tab; your session ends until you sign in again.
- **Delete your entire account** — see the [Delete your AURA account](#delete-your-aura-account) section above.

## Data retention

- Active accounts: we keep your data as long as your account exists.
- Deleted accounts: rows and files listed above are removed from active systems within minutes of the deletion request completing. Encrypted infrastructure backups may retain data for up to 30 days.
- Contact-discovery submissions: the raw identifiers your device sends for matching are discarded immediately after matching completes. Only the salted hashes of your **own** verified identifiers persist, and only while your account is active and discoverability is enabled.
- Report records may be retained in an anonymized form for abuse-prevention.

## Children

AURA is not intended for users under 13. If we learn we have inadvertently collected data from a child under 13, we will delete it promptly.

## Contact

Questions or requests about your data: **lead2ai.ops@gmail.com**.

## Changes

If we materially change this policy, we will update the "Last updated" date at the top and, where practical, surface a notice in the app.
