# Privacy Policy — OurRadioFS

_Last updated: 18 August 2026_

OurRadioFS is designed to collect **the bare minimum**. There are no accounts, no
sign-up, no email and no tracking. This policy explains the little data that is
involved and why.

## Data controller

**Miquel Angel** — Contact: **ourradiofs@outlook.com**

## What data is involved

- **Callsign:** an identifier you choose yourself. It does **not** have to be your
  real name; it can be any alias. It is shown to other pilots on your frequency.
- **Voice:** while you press push-to-talk, your voice is relayed in real time to the
  other pilots on your frequency and zone. It is **never recorded or stored**.
- **IP address:** like any internet service, the voice server sees your IP address in
  order to establish the connection, and it may appear briefly in the server's
  connection logs. It is **not** used to identify you, profile you, or for advertising.
- **Your simulated aircraft's position:** the latitude, longitude and altitude of the
  aircraft **inside your flight simulator** — never your real-world location. It is
  shared with the other pilots connected to the service so the app can work out who is
  close enough to hear you, which is the whole point of a VHF radio. Along with it go
  the frequencies you are tuned to and your aircraft type. If your aircraft has two
  radios and you listen to both, both frequencies are involved.

## The live map (on by default, and you can turn it off)

While you are flying, the following is published to a public map so other pilots can
find someone to fly with:

- your callsign, aircraft type and the frequencies you are tuned to — both, if you fly
  with two radios — including which one you transmit on;
- **where you are heading, only if you use SimBrief.** If you enter a SimBrief Pilot ID in
  Settings (see *Third parties*), your app reads the destination airport from your own flight
  plan and it is shown on the map. Leave that box empty and nothing about your route is ever
  published.
  - It is shown only **while you are flying**, and it is cleared when your flight ends. It is
    never saved to disk, so it cannot reappear on a later flight.
  - A flight plan is only used if it **matches the flight you are actually making**: it must
    depart from the airport you took off from, and it must be recent. An old plan is never
    published.
  - So the map can draw your route, we also work out **which airport you took off from**. We
    match the position where your flight started against a public list of airports. It comes
    from the position we already publish, and if you did not start near an airport, none is
    shown.
- your simulated aircraft's position, heading, ground speed and vertical speed;
- whether you are transmitting right now, so the map can show who is talking.
  **Nothing is recorded.** The app sends one signal when you press your push-to-talk key
  and another when you release it; the server keeps only that live on/off state in
  memory, drops it the moment you stop, and drops it by itself within seconds if your
  connection fails. **How long or how often you talk is never measured, counted, logged
  or stored**, and none of it is ever written to disk.

**Since version 1.6.0 this is on by default.** It used to be off unless you ticked it.
We changed it because a map that looks empty makes people think nobody is on the air,
when in fact there are pilots flying — and finding someone to talk to is the whole point
of the app. This is also how VATSIM, IVAO and similar services work.

**Nobody is switched on silently.** The choice is shown to you when you first run the
app, in the same notice where you accept the terms, with a box you can untick right
there. Because this change affects what is published about you, everyone who already had
the app is shown that notice again on updating — so if you would rather not appear, you
decide before anything is published.

You can also turn it off at any time in Settings (**"Show me on the live map"**), and you
then disappear from the map within about two minutes. With it off, none of this is ever
published: your position is then only used to work out radio range.

The map is **public**: anyone can open it, without an account.

## What stays on your device / what we do NOT do

- **We do not record or store audio.** Voice is relayed live and disappears.
- **We do not collect email, names or accounts.** There is no registration.
- We do not sell or share data for commercial purposes, and we use no tracking cookies
  or advertising.

## Donations

Donations are entirely **voluntary** and are handled by **Ko-fi**. If you choose to
donate, you interact with Ko-fi directly under their own privacy policy. OurRadioFS
does **not** receive or store your payment details or email, and donating unlocks
nothing — the app is fully free either way.

## Legal basis

Where a legal basis is required (for example under the EU/UK GDPR), the processing
relies on our **legitimate interest** in operating the service and keeping it secure:
routing your voice to the right frequency and accepting your network connection
(callsign, voice relay, IP address).

## Retention

- **Voice:** not retained at all (live relay only).
- **Callsign:** exists only for the duration of your session; not stored afterwards.
- **IP address:** only in the server's connection logs, for a short time, for security.
- **Simulated position:** held only while you are flying, to work out radio range. If you
  enable the live map, the map holds your last position for about two minutes and then
  drops it. Nothing is kept afterwards and no history or track is stored.
- **Whether you are transmitting:** a live on/off state, held in memory only while you
  are actually transmitting and cleared within seconds of you stopping. It is never
  written to disk, never logged, and no history, duration or count is ever built from it.

## Third parties

- **Voice server / hosting provider:** relays your voice in real time. No recording is
  produced.
- **SimBrief:** only if you choose to enter a SimBrief Pilot ID in Settings. Your app
  then asks SimBrief for your latest flight plan, **directly from your computer**. Your
  Pilot ID is never sent to our servers, and we never see your flight plan: the app keeps
  only the destination airport code, and only if that plan matches the airport you
  actually took off from. Leave the box empty and your app never contacts SimBrief at
  all.
- **Ko-fi:** only if you choose to donate, and only through Ko-fi's own systems.

These providers process data under their own policies.

## Your rights

Wherever you live, you can contact us with any privacy question or request — such as
to access, correct or delete whatever data relates to you — at
**ourradiofs@outlook.com**. Because we hold almost nothing about you, there is
usually little to act on.

Depending on your country, you may have specific rights under local law (for example
the EU/UK GDPR, Brazil's LGPD, or similar). Residents of the EU/EEA may also lodge a
complaint with their local data protection authority (in Spain, the AEPD).

## Changes

This policy may be updated. The current version is always published alongside the app.
