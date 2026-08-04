# Teledyne Technologies (teledyne-technologies)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Teledyne Technologies Incorporated is a leading provider of sophisticated digital imaging products and software, instrumentation, aerospace and defense electronics, and engineered systems. Headquartered in Thousand Oaks, California, Teledyne serves the defense, commercial, and industrial markets. Key subsidiaries include Teledyne FLIR (thermal imaging cameras and systems), Teledyne LeCroy (oscilloscopes and protocol analyzers), Teledyne Imaging (scientific and industrial cameras), and Teledyne API (air quality monitoring instruments). Teledyne FLIR provides REST APIs and SDKs for thermal camera integration, while Teledyne LeCroy provides ActiveDSO and VISA-based automation APIs for test and measurement instruments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Aerospace
- Defense
- Digital Imaging
- Instrumentation
- Thermal Imaging
- Test and Measurement
- Fortune 500

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### Teledyne FLIR Camera REST API

Teledyne FLIR provides REST API access for automation cameras (A50/A70, A400/A500/A700, Ax8 series). The API enables retrieval of thermal images, region of interest (ROI) data, alarm data, and camera configuration. Endpoints return radiometric JPEG images and JSON data for temperature measurements across spots, boxes, lines, polylines, and delta measurements. Used for industrial process monitoring, building inspection, and predictive maintenance applications. A Swagger/OpenAPI JSON specification is available from the camera's local web server.

- **Human URL:** [https://www.flir.com/support-center/Instruments/restful-api-exercise/](https://www.flir.com/support-center/Instruments/restful-api-exercise/)
- **Base URL:** `http://{camera_ip}/api`

#### Tags

- Thermal Imaging
- Camera
- REST API
- Industrial
- Machine Vision

#### Properties

- [Documentation](https://www.flir.com/support-center/Instruments/restful-api-exercise/)
- [OpenAPI](openapi/teledyne-flir-camera-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teledyne-flir-camera-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teledyne-flir-camera-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/teledyne-flir-measurement-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/teledyne-flir-alarm-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Teledyne FLIR Spinnaker SDK

The Spinnaker SDK provides programmatic control of Teledyne FLIR and DALSA machine vision cameras over USB3, GigE, 5GigE, and 10GigE interfaces. Supports C++, C#, Python, and Java with a cross-platform API for camera discovery, configuration, image acquisition, and processing. Includes SpinView GUI for camera exploration and real-time viewing. Used for factory automation, quality inspection, and scientific imaging applications.

- **Human URL:** [https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks](https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks)
- **Base URL:** `https://www.flir.com`

#### Tags

- Machine Vision
- Camera
- SDK
- Industrial Automation
- Image Acquisition

#### Properties

- [Documentation](https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks)
- [SDK](https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks)
- [Git Hub](https://github.com/Teledyne-MV/Spinnaker-Examples)
- [Postman Collection](collections/teledyne-flir-camera-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teledyne-flir-camera-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teledyne FLIR Mobile SDK

The FLIR Mobile SDK enables iOS and Android developers to build mobile applications that integrate thermal imaging capabilities from Teledyne FLIR professional thermal cameras. Supports data collection from connected thermal cameras and metering devices. Available through FLIR's Developer Program with approved access. Includes an App Gallery for showcasing third-party thermal imaging applications.

- **Human URL:** [https://www.flir.com/developer/mobile-sdk/](https://www.flir.com/developer/mobile-sdk/)
- **Base URL:** `https://www.flir.com/developer`

#### Tags

- Mobile SDK
- iOS
- Android
- Thermal Imaging
- Developer Program

#### Properties

- [Documentation](https://www.flir.com/developer/mobile-sdk/)
- [Developer Portal](https://www.flir.com/developer/mobile-sdk/)
- [Postman Collection](collections/teledyne-flir-camera-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teledyne-flir-camera-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teledyne LeCroy ActiveDSO API

ActiveDSO is Teledyne LeCroy's ActiveX/COM control enabling remote automation of MAUI-based oscilloscopes from Windows applications via SCPI commands, VISA drivers, Ethernet (ENET), GPIB, and USBTMC interfaces. Supports Python, C++, C#, LabVIEW, and MATLAB automation. Used for automated test sequences, waveform capture, protocol analysis, and measurement reporting in test and measurement workflows.

- **Human URL:** [https://www.teledynelecroy.com/support/techlib/programmingexamples.aspx](https://www.teledynelecroy.com/support/techlib/programmingexamples.aspx)
- **Base URL:** `https://www.teledynelecroy.com`

#### Tags

- Oscilloscope
- Test and Measurement
- Automation
- SCPI
- VISA

#### Properties

- [Documentation](https://www.teledynelecroy.com/support/techlib/programmingexamples.aspx)
- [Documentation](https://cdn.teledynelecroy.com/files/manuals/activedso-developers-guide.pdf)
- [Postman Collection](collections/teledyne-flir-camera-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teledyne-flir-camera-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.teledyne.com/en-us)
- [Developer Portal](https://www.flir.com/developer/mobile-sdk/)
- [Git Hub](https://github.com/FLIR)
- [Git Hub](https://github.com/Teledyne-MV)
- [Website](https://www.teledynelecroy.com/)
- [Website](https://www.teledyneimaging.com/)
- [Website](https://www.teledyne-api.com/en-us)
- [LinkedIn](https://www.linkedin.com/company/teledyne-technologies)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
