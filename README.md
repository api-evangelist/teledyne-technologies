# Teledyne Technologies (teledyne-technologies)

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
