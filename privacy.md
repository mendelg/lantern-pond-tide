# Lantern Pond — Privacy Policy

Last updated: July 14, 2026

Lantern Pond is playable without an account. It uses Firebase Authentication
and Cloud Firestore for optional sign-in and cloud saving, Firebase Analytics
to understand app and level use, and Firebase App Check to protect Firebase
services from abuse.

## Information used

### Local progress, accounts, and cloud saves

- Guest progress stays on the device, and no Firebase account is created until
  you choose to sign in. Purchases and Store-provided purchase restoration do
  not require an account. If you choose an account, cloud save can carry game
  progress, coin balance, and cosmetics to another device.
- You may use Sign in with Apple, Google sign-in, or an email address and
  password. Email login uses the address for sign-in and password recovery.
  Firebase Authentication processes the password; Lantern Pond does not store
  it or include it in cloud saves or Analytics. Apple or Google may provide
  Firebase with basic account information such as an email address and display
  name. Apple may provide a private relay email address if you choose **Hide My
  Email**. Apple and Google can each be linked to the same account as email
  sign-in.
- Firebase Authentication assigns an account identifier and may process
  standard security information such as an IP address and device or browser
  information to authenticate users and prevent abuse.
- Cloud saves are attached to the Firebase account identifier and contain game
  progress such as stars, XP, coin balance, streaks, owned and selected themes
  or lanterns, gameplay records, and purchase transaction identifiers used to
  prevent duplicate delivery.

### Analytics

- Firebase Analytics records app opens and sessions, screen visits, level
  starts and completions, in-app purchase events, and general app and device
  information. Purchase events may include the product identifier and price,
  but never payment-card details.
- Analytics uses a random app-installation identifier. It may derive an
  approximate country, region, or city from the network address used for the
  request. Lantern Pond does not request or access precise device location.
- Lantern Pond does not send your Firebase login identifier, name, or email
  address to Analytics.

### App protection and remote levels

- Firebase App Check uses app and device attestation signals and temporary
  App Check tokens to help confirm that requests come from the authentic app.
- At launch, Lantern Pond downloads a small file of level definitions from
  GitHub ("The Tide Pool"). No account details or game progress are included in
  this request. As with loading a web page, the request may expose standard
  network information such as an IP address and device or user-agent
  information to GitHub.

## Purchases

Purchases are processed by Apple's App Store or Google Play. Lantern Pond
receives the product and transaction information needed to deliver a purchase
and prevent duplicate delivery, but does not receive payment-card details. An
account is not required to purchase or to restore Store-restorable purchases.
Consumable coin balances are not restored by the Store; players may optionally
use cloud save to carry their current balance to another device.

## What Lantern Pond does not do

- Lantern Pond contains no advertising. Advertising-identifier collection and
  ad-personalization signals are disabled for Analytics.
- Lantern Pond does not use data for cross-app tracking and does not sell
  personal information.
- Lantern Pond does not collect phone numbers or request precise location.

## Retention, signing out, and deletion

Guest progress is not uploaded. If you connect Apple, Google, and/or email,
your cloud progress is retained until you delete the account. Signing out
disconnects the account from that device but does not delete the account or its
cloud save.

You can delete the Firebase account and its cloud save inside **The Keeper's
Book → Cloud save → Delete cloud account**. Progress remaining locally on the
device can be erased with **Begin Again** or by deleting the app. Deleting the
Lantern Pond account does not delete an Apple or Google account or the purchase
history maintained by the App Store or Google Play.

Analytics events are not linked to the Firebase login account, so deleting the
account does not delete previously collected Analytics events. Those events
follow the retention settings of the Lantern Pond Google Analytics property.
Uninstalling Lantern Pond stops future collection from that installation.
Service-provider backup copies may remain for a limited period under the
provider's retention and security practices.

## Service providers

Firebase and Firebase Analytics are provided by Google. Their processing is
also governed by [Firebase Privacy and Security](https://firebase.google.com/support/privacy)
and the [Google Privacy Policy](https://policies.google.com/privacy). Sign-in
and purchases may also be governed by the policies of
[Apple](https://www.apple.com/legal/privacy/) or
[Google](https://policies.google.com/privacy). Remote level downloads are
served by GitHub and are also subject to the
[GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

Questions or privacy requests: developermendelg@gmail.com
