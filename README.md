# Privacy Policy — Mousehole

**App:** Mousehole
**Package name:** `ca.mousewurx.mousehole`
**Developer:** MouseWurX
**Last updated:** 25 October 2026

---

## The short version

Mousehole has no account, no sign-in, no analytics, no advertising and no
tracking. MouseWurX runs no server, so there is nowhere for your details to be
sent to us, and we never receive, see or store anything you put into the app.

## What the app stores, and where

The details you add (emails, usernames, names, phone numbers, domains and
cities), your results, your settings and any API keys you paste are stored on
your phone only. The sensitive parts are encrypted with a key held in the
Android Keystore, which never leaves the device. Nothing is backed up to the
cloud by the app.

## What leaves your phone

A check sends one item straight from your phone to the service that answers that
check, over an encrypted (HTTPS) connection. Nothing is routed through
MouseWurX. Specifically:

- An email address goes to breach and malware-log services when you run those
  checks.
- A username is requested from public websites, exactly as a normal visit to
  each site's profile page would be.
- A domain or IP address goes to DNS, domain-record (RDAP) and IP-lookup
  services.
- For a password check, only the first five characters of its scrambled (SHA-1
  hashed) form are sent, which cannot identify the password. The password itself
  never leaves the phone.
- Your router's hardware address (BSSID) goes to WiGLE, and only when you open
  Wi-Fi on the Map.
- Your public IP address goes to IP-lookup services when you check your home
  connection.
- A photo you choose for reverse image search has its metadata stripped first,
  then you hand it to the app you pick.

As with visiting any website, each service also sees your phone's IP address and
can keep its own logs under its own privacy policy. Turning on a VPN hides your
IP from them.

## Services a check may contact

Which ones depends on the tools you use:

- **Breaches and leaks:** XposedOrNot, Have I Been Pwned, Pwned Passwords.
- **Public profiles:** the roughly 690 websites in the WhatsMyName list, plus
  GitHub, GitLab, Mastodon, Bluesky and Keybase.
- **Domains:** Cloudflare's DNS-over-HTTPS resolver, rdap.org and crt.sh.
- **Your connection:** ipify, ipwho.is, IPinfo and Shodan.
- **Your Wi-Fi:** WiGLE.
- **Local incidents:** RansomLook, which is asked for every recent post and
  matched on your phone, so it is never told which city is yours.
- **Connection tests:** Google's captive-portal endpoint, which carries nothing
  about you.
- **Buying Pro:** Google Play Billing.

Services that need an API key are only contacted if you added that key yourself.
News searches (GDELT, Google News) and the other "check it yourself" buttons
open in your browser instead, so the app isn't the one making the request.

## What never leaves your phone

Photos and files you pick, the list of apps installed on your phone (used by App
Permission Review), Bluetooth tags detected nearby, your clipboard contents,
your name, your phone number, your cities, your saved results and your exposure
score. The app does not read or record your location. Wi-Fi on the Map asks for
location permission only because Android will not reveal the connected router's
address to an app without it.

Some screens offer buttons that open a search in your browser, for example news
about your city. Those are your own searches: the site sees them and they stay
in your browser history, but the app never makes the request.

## Permissions and why

| Permission | Why |
| --- | --- |
| Internet and network state | To run the checks you ask for. |
| Bluetooth scan | To detect nearby tracking tags. Flagged "never for location". |
| Approximate location | Only so Android will reveal your own router's address for Wi-Fi on the Map. Your position is not read. |
| Notifications | To tell you about re-check results and tracker alerts. |
| Biometric or screen lock | To confirm it's you before revealing a leaked value or an API key. |

Every permission is optional. Decline one and only the tool that needs it stops
working.

## Payments

Mousehole Pro is a one-time purchase handled entirely by Google Play. The app
never sees your payment details. Google tells the app only whether your Google
account owns the unlock. Refunds and order history are handled in Google Play.

## Children

Mousehole is not directed at children and is not intended for use by anyone
under 13.

## Deleting everything

Settings › About › Withdraw consent stops everything that runs by itself.
Uninstalling the app removes all of its stored data from your phone. Because
none of it was ever sent to us, there is nothing for you to ask us to delete.

## Changes

If the app starts sending something new to somewhere new, the disclosure is
shown again before that happens, and this policy is updated in the same app
release.

## Contact

MouseWurX — support@mousewurx.ca
