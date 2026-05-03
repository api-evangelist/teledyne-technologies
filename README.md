# Teledyne Technologies (teledyne-technologies)

Teledyne Technologies Incorporated is a leading provider of sophisticated digital imaging products and software, instrumentation, aerospace and defense electronics, and engineered systems. Key subsidiaries include Teledyne FLIR (thermal imaging), Teledyne LeCroy (oscilloscopes and protocol analyzers), Teledyne Imaging (scientific cameras), and Teledyne API (air quality instruments). Teledyne FLIR provides REST APIs for thermal automation cameras and SDKs for machine vision cameras.

**URL:** [https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Fortune:** Fortune 500

## Tags:

 - Aerospace, Defense, Digital Imaging, Instrumentation, Test and Measurement, Thermal Imaging

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### Teledyne FLIR Camera REST API

REST API for FLIR automation cameras (A50/A70, A400/A500/A700, Ax8) - thermal images, ROI measurements, alarm monitoring.

**Human URL:** [https://www.flir.com/support-center/Instruments/restful-api-exercise/](https://www.flir.com/support-center/Instruments/restful-api-exercise/)

**Base URL:** `http://{camera_ip}/api`

#### Tags:

 - Camera, Industrial, Machine Vision, REST API, Thermal Imaging

#### Properties

- [Documentation](https://www.flir.com/support-center/Instruments/restful-api-exercise/)
- [OpenAPI](openapi/teledyne-flir-camera-rest-openapi.yml)
- [JSONSchema](json-schema/teledyne-flir-measurement-schema.json)
- [JSONSchema](json-schema/teledyne-flir-alarm-schema.json)

### Teledyne FLIR Spinnaker SDK

Machine vision camera SDK for USB3/GigE cameras in C++, C#, Python, and Java.

**Human URL:** [https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks](https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks)

#### Tags:

 - Image Acquisition, Industrial Automation, Machine Vision, SDK

#### Properties

- [Documentation](https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks)
- [SDK](https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks)
- [GitHub](https://github.com/Teledyne-MV/Spinnaker-Examples)

### Teledyne FLIR Mobile SDK

iOS/Android SDK for mobile applications integrating FLIR thermal cameras.

**Human URL:** [https://www.flir.com/developer/mobile-sdk/](https://www.flir.com/developer/mobile-sdk/)

#### Tags:

 - Android, Developer Program, iOS, Mobile SDK, Thermal Imaging

#### Properties

- [Documentation](https://www.flir.com/developer/mobile-sdk/)
- [DeveloperPortal](https://www.flir.com/developer/mobile-sdk/)

### Teledyne LeCroy ActiveDSO API

Remote automation API for MAUI oscilloscopes via SCPI, VISA, and ActiveX/COM.

**Human URL:** [https://www.teledynelecroy.com/support/techlib/programmingexamples.aspx](https://www.teledynelecroy.com/support/techlib/programmingexamples.aspx)

#### Tags:

 - Automation, Oscilloscope, SCPI, Test and Measurement, VISA

#### Properties

- [Documentation](https://www.teledynelecroy.com/support/techlib/programmingexamples.aspx)
- [Documentation](https://cdn.teledynelecroy.com/files/manuals/activedso-developers-guide.pdf)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [teledyne-flir-camera-rest-openapi.yml](openapi/teledyne-flir-camera-rest-openapi.yml) | FLIR Camera REST API - images, ROI measurements, alarms |

### JSON Schemas

| File | Description |
|---|---|
| [teledyne-flir-measurement-schema.json](json-schema/teledyne-flir-measurement-schema.json) | Schema for spot and box temperature measurement objects |
| [teledyne-flir-alarm-schema.json](json-schema/teledyne-flir-alarm-schema.json) | Schema for FLIR camera alarm objects |

### JSON Structure

| File | Description |
|---|---|
| [teledyne-flir-measurement-structure.json](json-structure/teledyne-flir-measurement-structure.json) | Field documentation for measurement objects |

### JSON-LD Context

| File | Description |
|---|---|
| [teledyne-technologies-context.jsonld](json-ld/teledyne-technologies-context.jsonld) | Linked data context mapping FLIR terms to SOSA/QUDT/schema.org |

### Examples

| File | Description |
|---|---|
| [teledyne-get-spot-measurement-example.json](examples/teledyne-get-spot-measurement-example.json) | Example request/response for spot temperature measurement |
| [teledyne-get-box-measurement-example.json](examples/teledyne-get-box-measurement-example.json) | Example request/response for box ROI measurement |
| [teledyne-get-all-alarms-example.json](examples/teledyne-get-all-alarms-example.json) | Example request/response for alarm states |

### Spectral Rules

| File | Description |
|---|---|
| [teledyne-technologies-rules.yml](rules/teledyne-technologies-rules.yml) | Spectral ruleset for Teledyne API conventions |

### Naftiko Capabilities

| File | Description |
|---|---|
| [capabilities/industrial-thermal-monitoring.yaml](capabilities/industrial-thermal-monitoring.yaml) | Industrial thermal monitoring workflow (6 MCP tools) |
| [capabilities/shared/flir-camera-rest.yaml](capabilities/shared/flir-camera-rest.yaml) | Shared FLIR Camera REST API consumed definition |

### Vocabulary

| File | Description |
|---|---|
| [teledyne-technologies-vocabulary.yml](vocabulary/teledyne-technologies-vocabulary.yml) | Domain vocabulary for Teledyne thermal imaging and instrumentation |

## Common Properties

- [Website](https://www.teledyne.com/en-us)
- [FLIR Developer Program](https://www.flir.com/developer/mobile-sdk/)
- [Teledyne FLIR GitHub](https://github.com/FLIR)
- [Teledyne Machine Vision GitHub](https://github.com/Teledyne-MV)
- [Teledyne LeCroy](https://www.teledynelecroy.com/)
- [Teledyne Imaging](https://www.teledyneimaging.com/)
- [Teledyne API](https://www.teledyne-api.com/en-us)
- [LinkedIn](https://www.linkedin.com/company/teledyne-technologies)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
