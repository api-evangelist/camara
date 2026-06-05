# CAMARA (camara)

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
