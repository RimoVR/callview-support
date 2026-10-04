# Callview Privacy Policy

**Effective date: 4 October 2026**

Callview is a read-only CT review client for authorized CHILI WebViewer users.
This policy describes Callview version 2.0 and its handling of information.

## Clinical information and service access

When you sign in, Callview sends the authentication and study requests needed
for your chosen workflow to your organization's CHILI service. It processes
the credentials, session state, study metadata and images returned by that
service. These can include personal and health information.

Your organization operates the clinical service, controls who can access its
records, and determines its own retention, logging and privacy practices.
Callview does not create or change clinical records, send patient data to the
Callview developer, sell data, or use clinical information for advertising.

## Information on your device

Clinical metadata and images remain session-bound in memory. Already-admitted
image data may also use a temporary encrypted, application-private cache. Its
key exists only in memory for the session. The app removes the cache on normal
session cleanup and cleans up leftovers after an interrupted session; loss of
the session key makes leftover encrypted data unreadable. Raw DICOM files and
unfiltered clinical metadata are not retained as a persistent library.

If you choose to remember access, credentials are stored in the operating
system's protected credential store. Normal sign-out does not remove remembered
credentials. Use **Gespeicherten Zugang vergessen** on the login screen to
remove them. Removing the app may not remove credentials retained by that
secure store. Nonclinical viewer preferences are stored locally.

## Demonstration and external links

The built-in offline demonstration uses bundled, licensed veterinary CT images
with no human patient data. It does not require a clinical account or connect
to the CHILI service. Opening support, privacy or attribution links launches
your browser and connects to the selected website, which has its own privacy
policy. No patient data is included in those links.

Callview has no advertising, analytics, tracking or social-login SDKs. Apple
handles App Store and TestFlight distribution under its own terms and privacy
practices. Where an update destination is configured, update checks retrieve
public release information without credentials or clinical identifiers.

## Your choices and contact

Contact your organization for access, correction or deletion of information
held by its CHILI service. Callview cannot administer or delete that account.

For Callview privacy or support questions, email
[pmk@pmn.de](mailto:pmk@pmn.de) or open a
[support issue](https://github.com/RimoVR/callview-support/issues). Information
you send for support is used to respond to your request. GitHub issues are
public: do not include patient information, clinical screenshots, credentials
or private service addresses.

This policy is updated when the app's data practices change.
