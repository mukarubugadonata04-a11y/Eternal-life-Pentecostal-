# Eternal Life Pentecostal Church International — Premium Website Build

## What's included
- Multi-page responsive website: Home, About, Ministries, Youth Choir, Sermons & Media, Events, Humanitarian Outreach, Give, Prayer Requests and Contact.
- Elevated navy-and-gold identity with warm ivory surfaces, Playfair Display / DM Sans typography and responsive navigation.
- Church photography from the supplied original ZIP plus the newly supplied Youth Choir and worship photographs.
- Restrained photo enhancement derivatives (`*-web.jpg`) for website display. Original uploads are retained.
- Custom-amount one-time/monthly giving interface, anonymous giving option and intended payment-method presentation.
- Private prayer-request form concept with anonymous option.
- Administration dashboard visual prototype with planned prayer-request statuses.
- README deployment notes.

## Preview locally
This is a static front-end preview. You can open `index.html` directly, or run a local server from this folder:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Important: payment and private-data functions are not live
The donation and prayer forms are deliberately preview-only. They do not submit, store or charge anything. The dashboard is also a visual prototype, not an authenticated administrator system.

Before launch, the project needs a secure backend and database:
1. Church administrator completes Pesapal merchant onboarding and obtains production credentials.
2. Developer configures Pesapal API authentication, order submission, IPN registration and server-side transaction-status verification using the current Pesapal documentation and merchant account settings.
3. Confirm with Pesapal whether recurring/monthly billing is enabled for this merchant and which payment methods support it. Until confirmed, do not advertise monthly auto-debit as active. A monthly pledge/reminder workflow can be offered as a separate alternative.
4. Configure an SMS provider and sender ID for donor confirmations. SMS delivery is provider-dependent; email receipts can be added as a fallback.
5. Build authenticated admin access with role-based permissions, secure password hashing, session protection, audit logs and server-side validation.
6. Store prayer requests and donor data securely with access controls, retention rules, backups and a privacy notice. Never store card details.
7. Configure HTTPS, environment secrets, webhook/IPN validation, rate limiting, spam protection and production monitoring.
8. Test sandbox transactions, failed/cancelled payments, duplicate notifications, refunds/reconciliation and mobile layouts before enabling live payments.

## Business details used
- Church: Eternal Life Pentecostal Church International
- Head pastor: Pastor Sebuhoro Daniel
- Location: Mutundwe, Kampala, Wakiso District, Uganda
- Established: 2017; officially opened: 2018
- Sunday service: 10:00 AM–1:00 PM
- Saturday service: 10:00 AM–4:00 PM
- Mission: To spread the Gospel, worship God and serve others; to make disciples of Jesus Christ, and to teach them what Jesus taught.
- General Charitable Fund: intended to help refugee families and vulnerable individuals as the church expands its charitable initiative through donations.

## Content accuracy notes
- The humanitarian outreach is described as an initiative the church intends to expand; no existing programme outcomes or beneficiary counts are claimed.
- No separate vision statement or additional leaders were supplied, so none are invented.
- No unconfirmed events are listed.
- Youth Choir photos are labelled as Youth Choir assets.
- Pastor name is written as **Sebuhoro Daniel**.
