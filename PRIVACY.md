# Privacy Policy – Voltframe

Last updated: 2026-11-25 · © 2026 reophyva

**Short version:** Voltframe does not collect, sell or send your personal data to the developer.
Everything it reads stays on your device.

## What the app reads on your device, and why

- **Installed apps** (names, icons, "game" category): to show your games and send the games you pick to
  Xiaomi's PowerKeeper service on your device.
- **Which app is on screen** (only if you allow *Usage access*): to switch per-game color profiles and to
  show the overlay or edge handle only while gaming.
- **Frame timing and temperatures** (only if you grant `DUMP` over ADB): read from Android's display and
  thermal services for the in-game overlay. The app does not read notifications, accounts or any other
  system data, even though this permission would technically allow it.
- **Screen brightness, your default keyboard and launcher, and memory use**: for the Quick Panel (your
  keyboard and launcher are never closed).

## What the app changes (only when you use these features)

- Screen brightness and auto-brightness.
- Night Light, Extra dim and Colour correction (color profiles, only after a one-time ADB grant). Your
  own values are saved first and given back.
- The high-refresh-rate game list in Xiaomi PowerKeeper.

## What is stored, and where

Your settings, chosen games, per-game profiles and recent frame-rate results are stored only in the
app's private storage on your device. They are **not** included in cloud backups or device transfers.
Entries for apps you uninstall are deleted automatically.

Delete everything at any time with **Voltframe → About → Delete my Voltframe data**, or by uninstalling.

## What leaves your device

Only update checks. Every 12 hours on Wi-Fi (or when you tap *Check for updates*), the app contacts
GitHub (`api.github.com`) and may download a new version from GitHub. GitHub receives your IP address
and the generic name `Voltframe-Updater`, as with any web request; see
[GitHub's privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
No identifiers, app lists or usage data are sent. Turn off **Auto-update** to stop this.

No analytics, no ads, no accounts, no tracking. Voltframe is not directed at children.

## Contact

Open an issue at https://github.com/reophyva/voltframe. Changes to this policy will be published in this
file.
