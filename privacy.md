---
title: Privacy Policy
---

# Backd — Privacy Policy

_Last updated: June 26, 2026._

Backd is an accountability app. Our guiding rule is **private by default**: your
data is visible to you, and only to the specific friends you choose to be
accountable to — never to the public, never sold, never used for advertising.

## Who we are
Backd ("we", "us") is operated by Anson Antony.
Contact: ansonkanniman@gmail.com.

## What we collect and why

**Account information.** Your email address and a display name, to create and
secure your account. If you sign in with Apple, we receive the name and the
private relay email you choose to share.

**Your goals and check-ins.** The goals you create, their schedules, and your
check-ins and outcomes — this is the core of the app.

**Proof you submit.** Photos, screenshots, or written notes you attach to a
check-in. Proof is visible only to you and to a friend you specifically assign to
review that goal. Proof photos are stored privately and are never public. You can
set how long proof media is retained (including "never store media") in Settings.

**Health data (optional).** If you choose an Apple Health proof type and grant
permission, Backd **reads** your step count and workouts from Apple Health on
your device to verify a health-related check-in. We only ever derive a result
(e.g. "met the step goal") and a step count — we never read your medical records,
never write to Apple Health, and never use Health data for advertising or share
it with third parties or other users.

**Location data (optional).** If you choose a location proof type and grant
permission, Backd captures your location **once, only at the moment you tap to
check in**, to verify you were at a place (like a gym or library). We never track
your location in the background. Coordinates recorded with a check-in are rounded
to roughly 110 meters so a reviewing friend can corroborate the place without
your exact spot being exposed.

**Google Calendar (optional).** If you connect Google Calendar, Backd requests
only the calendar-events permission. We use it to (a) read your upcoming events so
you can turn one into a goal, and (b) add your goals to your calendar as events —
both at your request. We store the Google access token privately, linked to your
account under row-level security; it is never logged and never shown to friends.
We do not read or store your calendar beyond what's needed for these actions, and
you can disconnect at any time, which removes the stored token.

**Canvas (optional).** If you connect Canvas, you enter your school's Canvas URL
and a personal access token. We store that token privately, linked to your account
under row-level security; it is never logged and never shown to friends. We use it
only to read your upcoming assignments so you can turn one into a goal — Backd never
creates a goal without you confirming it, and never writes anything back to Canvas.
You can disconnect at any time, which removes the stored token.

**AI proof review (optional).** On a proof review screen you can tap "Run AI check"
to get an automated second opinion on a submission. When you do, and only then, the
proof image and a short text description are sent to a third-party AI vision provider
to return an advisory result. The AI never has the final say — you or your assigned
friend always make the real decision, and the check runs only when you tap it (never
automatically). You can ignore or turn this off; it is not required to use Backd.

**Photo metadata.** Proof photos are re-encoded when captured, which removes
embedded camera/EXIF metadata (including any GPS location) before the image is
stored. We do not read or store the original photo's location metadata.

**Screen Time / Focus Vault (optional, iOS).** If you use the Focus Vault to
shield distracting apps on your own device, the set of apps you choose stays on
your device as opaque system tokens — Backd cannot read which apps they are, and
never uploads them. We store only a count (e.g. "12 apps") and a label you type.
The shield is self-imposed and you can lift it at any time; it is also cleared
automatically when you sign out or delete your account. Backd never blocks app
removal and never controls anyone else's device.

**Friends and accountability.** The friends/buddies you connect with, and which
goals you assign them to review. A friend sees only the proof for goals you
assign them, plus whatever you choose to share in Settings (e.g. streak numbers,
trophies). Your stakes, journal entries, exact location, raw health data,
calendar, and other goals are never shown to friends.

**Notifications.** If you enable reminders or remote notifications, we store a
device push token to deliver them. Notification content is kept generic on the
lock screen and does not reveal your specific goals or any money figures.

**Diagnostics (optional).** If enabled, we collect crash and error reports that
contain only non-identifying labels and a redacted error message (emails, URLs,
tokens, and phone numbers are stripped before anything is sent). No proof, goal
text, or journal content is included.

**No payments.** Backd does not process real-money payments. Stakes are tracked
manually for your own motivation; no money moves through the app.

## How your data is protected
Every record is protected by row-level security so that, by default, only you can
read or write your own data. The only cross-user access is the narrow, relationship
-scoped review described above. Data is stored with our infrastructure provider,
Supabase (Postgres + Storage), encrypted in transit.

## Sharing
We do **not** sell your data and do **not** use it for advertising. We share data
only with the infrastructure providers needed to run the app (e.g. Supabase for
storage/database; Apple for push delivery; Twilio for SMS reminders if you opt in;
and, only when you tap "Run AI check", a third-party AI vision provider that returns
an advisory proof result). We may disclose data if required by law.

## Your controls
- **Edit what friends can see** in Settings → privacy toggles.
- **Set proof-media retention** (including "never store media").
- **Delete your account** at any time in Settings → Delete account. This
  permanently deletes your account and all associated data — goals, check-ins,
  proof media (swept from storage), stakes, trophies, and friend links. Any stored
  Google Calendar or Canvas tokens are deleted, and any on-device Focus Vault
  shield is cleared. This cannot be undone.
- **Delete proof media only** at any time in Settings → Delete all proof media
  (keeps your check-in history, removes the photos from storage).
- **Revoke Health or Location** permission any time in iOS Settings.

## Children
Backd is not directed to children under 13 (or the minimum age in your region).

## Changes
We'll update this policy as the app evolves and revise the date above.

## Contact
ansonkanniman@gmail.com
