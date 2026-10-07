# BrewHaha privacy policy

Effective 7 October 2026. BrewHaha is developed by Christian Brooker (JediBrooker).

BrewHaha helps you plan recipes and record your brewing. It does not require a BrewHaha account and has no advertising or analytics SDK.

## Your brewing records

Recipes, equipment profiles, batches, tasting notes, ratings, fermentation readings, pantry items and brew sessions are stored on your device. BrewHaha does not upload these records to an app account or developer server; only recipes you choose to share with the community leave your device (see Community recipes below). Apple may include app data in device backups according to your device settings.

You can export a backup and choose where to save or share it. Imported backups are processed on your device. Copies you export remain in the locations you choose; manage those copies separately.

## Camera, Bluetooth and location

The camera reads ingredient barcodes on your device. Camera images are not uploaded. A scanned code first matches saved pantry items locally.

Compatible Tilt hydrometers broadcast their readings as Bluetooth beacons, so Bluetooth must be turned on to read them. iOS only lets apps receive these beacon broadcasts through its location services. When you tap **Scan** to find a Tilt, BrewHaha therefore asks for location access while the app is in use. BrewHaha uses this permission only to detect nearby Tilt beacons. It does not read, store or share your location, and it never asks for location access in the background. Tilt readings are recorded in your local batch history. Without this permission, or without a Tilt, you can enter gravity and temperature readings manually.

You can manage camera and location permissions in iOS Settings.

## Optional online product lookup

Only when you choose **Look up product online**, BrewHaha sends the product barcode to Open Food Facts. Its servers also receive your IP address and an app identification header containing the app name, version and support URL. Camera images, recipes, batch records and pantry contents are not sent.

[Open Food Facts' privacy policy](https://world.openfoodfacts.org/privacy) states that visitor IP addresses and request logs are retained for three years for security, technical analysis and popularity measurement. Open Food Facts operates this service under its own policy. You can contact it at privacy@openfoodfacts.org about its handling of those records. BrewHaha uses Apple's native barcode scanning, without Google's MLKit scanner.

Online lookup is optional. Local matching and manual product entry remain available without it. Product facts are community contributed; check the packaging before saving. [Open Food Facts data](https://world.openfoodfacts.org/data) is licensed under the [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/).

## Community recipes

Community recipes are optional. Browsing them needs no identity. Nothing about you is sent until you share, rate or report a recipe. Then this installation gets an anonymous community identity: a random ID and a key kept in your device's keychain. No name, email address or account is needed.

**Public:** recipes you share, the display name you choose for them, and rating averages and counts.

**Stored on the BrewHaha server but not public:** your anonymous identity, which recipes you rated or reported, and report notes. Nothing links the identity to you as a person. The server does not store IP addresses; to limit abuse it keeps a salted fingerprint of the address, which changes daily and is deleted within two days.

**On your device only:** everything else, including your other recipes, batches, tasting notes, readings, pantry, display name setting and the authors you block.

The community server runs on Cloudflare, which processes these requests for BrewHaha under its [privacy policy](https://www.cloudflare.com/privacypolicy/). Shared recipes are checked automatically for blocked words and links. Recipes reported by several people are hidden and reviewed by the developer, who may remove them or block their author.

Because the identity is tied to this installation, deleting the app means you can no longer change or remove what you shared. Use **Settings → Community → Delete everything I shared** first: it removes your shared recipes, ratings, reports and community identity from the server.

## External links and support

When you open a recipe source, manufacturer manual, support page or other external link, your browser connects to that website. The website's own privacy policy applies. If you contact support, you choose which contact details, messages and attachments to provide. Avoid sending backups or private brewing notes unless needed to investigate the issue.

## This website

These public privacy and support pages are hosted by GitHub Pages. GitHub handles website requests under its [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). The pages contain no analytics scripts, advertising or third-party fonts. This website hosting is separate from the local brewing records in the app.

## Your choices

Delete individual records in the app, or remove its local database by deleting the app. Manage exported files and Apple device backups separately. Choose local barcode matching or manual entry to avoid online product lookup. Remove community recipes, ratings and reports with **Settings → Community → Delete everything I shared**. BrewHaha does not use this information for advertising tracking.

## Contact and updates

For privacy questions, [contact the developer through GitHub Issues](https://github.com/JediBrooker/BrewHaha/issues/new/choose). Issues are public: do not include personal information, backup files or private brewing notes. If your request needs private information, ask for a private contact channel first.

This policy will be updated if BrewHaha's data practices change. The effective date above identifies the current version.
