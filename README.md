# CAMARA (camara)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

CAMARA is an open-source Linux Foundation project developing standardized, open, and globally-available telecom APIs as part of the Telco Global API Alliance. Founded and supported by AT&T, Deutsche Telekom, Ericsson, Google Cloud, Microsoft, Nokia, Telefonica, Vodafone, GSMA, and many others, CAMARA defines consistent, operator-agnostic network capability APIs so developers can access programmable network services such as quality-on-demand, device location, SIM swap, number verification, and edge cloud across multiple carriers through a single, unified, standard API surface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/camara/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/camara/refs/heads/main/apis.yml)

## Scope

- **Position:** Provider
- **Access:** Open

## Tags

- Telecom
- Network APIs
- Standards
- Linux Foundation
- Open Gateway
- GSMA
- Connectivity
- 5G

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### CAMARA Quality On Demand API

The Quality On Demand (QoD) API allows applications to request on-demand, bounded-duration, guaranteed-quality network sessions for specific device flows (latency, throughput, priority class). Developers can set QoS profiles, receive events on session state changes, and manage sessions without dealing with operator-specific signalling.

- **Human URL:** [https://github.com/camaraproject/QualityOnDemand](https://github.com/camaraproject/QualityOnDemand)
- **Base URL:** `https://api.example.com/quality-on-demand/v0`

#### Tags

- Quality of Service
- Network
- QoD
- 5G

#### Properties

- [Documentation](https://github.com/camaraproject/QualityOnDemand)
- [Repository](https://github.com/camaraproject/QualityOnDemand)
- [OpenAPI](openapi/camara-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Device Location API

Provides location-verification, location-retrieval, and geofencing subscription endpoints allowing applications to confirm whether a mobile device is in a specified area, to retrieve the last known area the device connected from, and to receive asynchronous notifications when a device enters or leaves a geofenced region — all using operator network data rather than handset GPS.

- **Human URL:** [https://github.com/camaraproject/DeviceLocation](https://github.com/camaraproject/DeviceLocation)
- **Base URL:** `https://api.example.com/location/v0`

#### Tags

- Location
- Geofencing
- Network

#### Properties

- [Documentation](https://github.com/camaraproject/DeviceLocation)
- [Repository](https://github.com/camaraproject/DeviceLocation)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Number Verification API

Silent, cryptographically strong verification that the mobile number a user claims to own is actually the number of the SIM attached to the device making the request. Replaces SMS one-time-password flows with an operator-authenticated check over the data connection, reducing fraud and user friction in onboarding and login.

- **Human URL:** [https://github.com/camaraproject/NumberVerification](https://github.com/camaraproject/NumberVerification)
- **Base URL:** `https://api.example.com/number-verification/v0`

#### Tags

- Identity
- Authentication
- Anti-Fraud
- MSISDN

#### Properties

- [Documentation](https://github.com/camaraproject/NumberVerification)
- [Repository](https://github.com/camaraproject/NumberVerification)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA SIM Swap API

Detects whether the SIM attached to a given mobile number has recently been changed. Used by banks, crypto platforms, and other high-assurance services to mitigate SIM-swap account-takeover attacks before sending SMS OTPs or authorizing high-risk transactions.

- **Human URL:** [https://github.com/camaraproject/SimSwap](https://github.com/camaraproject/SimSwap)
- **Base URL:** `https://api.example.com/sim-swap/v0`

#### Tags

- Anti-Fraud
- Identity
- Security
- SIM

#### Properties

- [Documentation](https://github.com/camaraproject/SimSwap)
- [Repository](https://github.com/camaraproject/SimSwap)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Device Status API

Provides queries and event subscriptions about a mobile device's connectivity status (reachable, connected, roaming) so applications can adapt behaviour, trigger retries, or switch channels based on real-time network reachability.

- **Human URL:** [https://github.com/camaraproject/DeviceStatus](https://github.com/camaraproject/DeviceStatus)
- **Base URL:** `https://api.example.com/device-status/v0`

#### Tags

- Connectivity
- Roaming
- Events

#### Properties

- [Documentation](https://github.com/camaraproject/DeviceStatus)
- [Repository](https://github.com/camaraproject/DeviceStatus)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Simple Edge Discovery API

Returns the closest Mobile Edge Cloud (MEC) endpoint for a given device based on operator network topology, allowing edge-native applications to connect to the lowest-latency edge zone without embedding operator- specific logic.

- **Human URL:** [https://github.com/camaraproject/SimpleEdgeDiscovery](https://github.com/camaraproject/SimpleEdgeDiscovery)
- **Base URL:** `https://api.example.com/simple-edge-discovery/v0`

#### Tags

- Edge
- MEC
- Latency

#### Properties

- [Documentation](https://github.com/camaraproject/SimpleEdgeDiscovery)
- [Repository](https://github.com/camaraproject/SimpleEdgeDiscovery)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Edge Application Management API

Lifecycle APIs for deploying, managing, and terminating edge-native application instances across operator Mobile Edge Cloud infrastructure, enabling developers to place workloads close to end users without operator lock-in.

- **Human URL:** [https://github.com/camaraproject/EdgeApplicationManagement](https://github.com/camaraproject/EdgeApplicationManagement)
- **Base URL:** `https://api.example.com/edge-application-management/v0`

#### Tags

- Edge
- MEC
- Deployment

#### Properties

- [Documentation](https://github.com/camaraproject/EdgeApplicationManagement)
- [Repository](https://github.com/camaraproject/EdgeApplicationManagement)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Device Identifier API

Returns a privacy-preserving identifier for a device associated with a network-attached session, enabling correlation and authentication flows while minimising exposure of raw MSISDNs or IMEIs.

- **Human URL:** [https://github.com/camaraproject/DeviceIdentifier](https://github.com/camaraproject/DeviceIdentifier)
- **Base URL:** `https://api.example.com/device-identifier/v0`

#### Tags

- Identity
- Privacy

#### Properties

- [Documentation](https://github.com/camaraproject/DeviceIdentifier)
- [Repository](https://github.com/camaraproject/DeviceIdentifier)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Home Devices Quality On Demand API

Extends Quality On Demand semantics to fixed-line / home broadband devices, allowing applications to request guaranteed bandwidth or low-latency sessions for devices attached to a home gateway.

- **Human URL:** [https://github.com/camaraproject/HomeDevicesQoD](https://github.com/camaraproject/HomeDevicesQoD)
- **Base URL:** `https://api.example.com/home-devices-qod/v0`

#### Tags

- Broadband
- Home
- QoS

#### Properties

- [Documentation](https://github.com/camaraproject/HomeDevicesQoD)
- [Repository](https://github.com/camaraproject/HomeDevicesQoD)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Connectivity Insights API

Exposes network insight data such as historical and real-time network quality, congestion, and throughput characteristics for a subscriber context, letting applications tune streaming, uploads, and sync behaviour to current network conditions.

- **Human URL:** [https://github.com/camaraproject/ConnectivityInsights](https://github.com/camaraproject/ConnectivityInsights)
- **Base URL:** `https://api.example.com/connectivity-insights/v0`

#### Tags

- Analytics
- Quality of Service
- Observability

#### Properties

- [Documentation](https://github.com/camaraproject/ConnectivityInsights)
- [Repository](https://github.com/camaraproject/ConnectivityInsights)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CAMARA Identity and Consent Management API

Shared authorization and consent model across CAMARA APIs, built on OAuth 2.0 / OpenID Connect Client-Initiated Backchannel Authentication (CIBA) so subscribers explicitly consent to application use of network capabilities such as location, SIM-swap, or QoD on their behalf.

- **Human URL:** [https://github.com/camaraproject/IdentityAndConsentManagement](https://github.com/camaraproject/IdentityAndConsentManagement)
- **Base URL:** `https://api.example.com/identity-consent/v0`

#### Tags

- OAuth
- CIBA
- Consent
- Identity

#### Properties

- [Documentation](https://github.com/camaraproject/IdentityAndConsentManagement)
- [Repository](https://github.com/camaraproject/IdentityAndConsentManagement)
- [Postman Collection](collections/camara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/camara-project)
- [Website](https://camaraproject.org/)
- [Documentation](https://camaraproject.org/apis/)
- [Portfolio](https://camaraproject.github.io/releases/portfolio.html)
- [Git Hub Org](https://github.com/camaraproject)
- [Governance](https://github.com/camaraproject/Governance)
- [Commonalities](https://github.com/camaraproject/Commonalities)
- [Release Management](https://github.com/camaraproject/ReleaseManagement)
- [Linux Foundation Project](https://lfnetworking.org/projects/camara/)
- [JSON-LD](json-ld/camara-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary Definition](vocabulary.yml)
- [Spectral Rules](spectral/camara.spectral.yml)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
