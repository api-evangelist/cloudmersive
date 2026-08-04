# Cloudmersive (cloudmersive)

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

Cloudmersive provides a portfolio of utility APIs covering virus and malware scanning, document conversion, OCR, image recognition, NLP, validation, security threat detection (spam, phishing, fraud, DLP, CDR), speech, video, barcode, currency, and data integration. Each API is documented with a Swagger 2.0 / OpenAPI specification, has SDKs in multiple languages, and is consumable on api.cloudmersive.com behind an API key (`Apikey` header).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cloudmersive/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cloudmersive/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Barcodes
- Conversions
- Documents
- Image Recognition
- Natural Language
- OCR
- Processing
- Validation
- Virus Scanning

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-05-19

## APIs

### Cloudmersive Virus Scan API

Scan files and content for viruses, malware, executables, scripts, macros, password-protected files, and other content threats. Includes both basic and advanced (multi-engine) scan modes and a website scan.

- **Human URL:** [https://cloudmersive.com/virus-api](https://cloudmersive.com/virus-api)

#### Tags

- Antivirus
- Malware
- Security
- Virus Scanning

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Virus%20Scan%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/virus) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/cloudmersive-virus-scan-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Security Threat Detection API

Detect SQL injection, XSS, XXE, SSRF, command injection, and other content-borne attacks against text and HTML inputs.

- **Human URL:** [https://cloudmersive.com/security-threat-detection-api](https://cloudmersive.com/security-threat-detection-api)

#### Tags

- Security
- SQL Injection
- Threat Detection
- XSS

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Security%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/security) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Spam Detection API

AI-powered spam detection for email and message content.

- **Human URL:** [https://cloudmersive.com/spam-detection-api](https://cloudmersive.com/spam-detection-api)

#### Tags

- Email
- Spam

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Spam%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/spam) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Phishing Detection API

Detect phishing attempts in email content and URLs using AI scanning.

- **Human URL:** [https://cloudmersive.com/phishing-detection-api](https://cloudmersive.com/phishing-detection-api)

#### Tags

- Email Security
- Phishing

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Phishing%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/phishing) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Content Disarm and Reconstruction (CDR) API

Sanitize user documents by stripping macros, scripts, and other embedded threats while preserving usable content (Content Disarm and Reconstruction).

- **Human URL:** [https://cloudmersive.com/content-disarm-and-reconstruction-cdr-api](https://cloudmersive.com/content-disarm-and-reconstruction-cdr-api)

#### Tags

- CDR
- Document Sanitization
- Security

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=CDR%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/cdr) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Fraud Detection API

Document fraud and content security threat scanning.

- **Human URL:** [https://cloudmersive.com/fraud-detection-api](https://cloudmersive.com/fraud-detection-api)

#### Tags

- Fraud Detection
- Risk

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Fraud%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/fraud) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Data Loss Prevention (DLP) API

Detect and redact personally identifiable information (PII) and other sensitive data in text and documents.

- **Human URL:** [https://cloudmersive.com/data-loss-prevention-dlp-api](https://cloudmersive.com/data-loss-prevention-dlp-api)

#### Tags

- Compliance
- DLP
- PII

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=DLP%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/dlp) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Document Convert API

Convert files between many formats (DOCX/PDF/HTML/XLSX/PPTX/CSV/JSON/XML), take URL screenshots, edit documents, and process tabular data.

- **Human URL:** [https://cloudmersive.com/convert-api](https://cloudmersive.com/convert-api)

#### Tags

- Conversion
- Documents
- File Formats

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Convert%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/convert) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Barcode API

Generate and recognize barcodes including QR codes, EAN, UPC, Code 128, and more.

- **Human URL:** [https://cloudmersive.com/barcode-api](https://cloudmersive.com/barcode-api)

#### Tags

- Barcode
- QR Code

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Barcode%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/barcode) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Image Recognition and Processing API

Recognize and process images: classify, detect objects, NSFW detection, face detection, image editing, filters, and resizing.

- **Human URL:** [https://cloudmersive.com/image-recognition-and-processing-api](https://cloudmersive.com/image-recognition-and-processing-api)

#### Tags

- Computer Vision
- Image Processing
- Image Recognition

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Image%20Recognition%20and%20Processing%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/image) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Natural Language Processing API

Tokenization, POS tagging, sentence splitting, language detection, translation, sentiment analysis, and rephrasing.

- **Human URL:** [https://cloudmersive.com/natural-language-processing-api](https://cloudmersive.com/natural-language-processing-api)

#### Tags

- NLP
- Sentiment Analysis
- Translation

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Natural%20Language%20Processing%20(NLP)%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/nlp) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/nlpv2) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive OCR API

Deep-learning-based OCR for images and PDFs, with form, receipt, and business-card extraction.

- **Human URL:** [https://cloudmersive.com/ocr-api](https://cloudmersive.com/ocr-api)

#### Tags

- Documents
- OCR

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Optical%20Character%20Recognition%20(OCR)%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/ocr) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Speech API

Speech-to-text and text-to-speech in multiple languages.

- **Human URL:** [https://cloudmersive.com/speech-api](https://cloudmersive.com/speech-api)

#### Tags

- Speech
- Speech Recognition
- Text to Speech

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Speech%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/speech) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Validate API

Validate emails, phone numbers, domains, IP addresses, addresses, and other inputs.

- **Human URL:** [https://cloudmersive.com/validate-api](https://cloudmersive.com/validate-api)

#### Tags

- Email
- Validation

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Validate%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/validate) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Video API

Convert, edit, and process video and audio files.

- **Human URL:** [https://cloudmersive.com/video-api](https://cloudmersive.com/video-api)

#### Tags

- Conversion
- Video

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Video%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/video) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Currency API

Real-time currency exchange rates and conversions across major fiat and crypto currencies.

- **Human URL:** [https://cloudmersive.com/currency-api](https://cloudmersive.com/currency-api)

#### Tags

- Currency
- Exchange Rate

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Currency%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/currency) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Configuration API

Hosted configuration management and feature flag service.

- **Human URL:** [https://cloudmersive.com/config-api](https://cloudmersive.com/config-api)

#### Tags

- Configuration
- Feature Flags

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Config%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/config) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudmersive Data Integration API

Connect, transform, and integrate data across systems and file formats.

- **Human URL:** [https://cloudmersive.com/data-integration-api](https://cloudmersive.com/data-integration-api)

#### Tags

- Data Integration
- ETL

#### Properties

- [Documentation](https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Data%20Integration%20API)
- [OpenAPI](https://api-console.cloudmersive.com/swagger/api/dataintegration) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudmersive-virus-scan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudmersive-virus-scan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Cloudmersive)
- [LinkedIn](https://www.linkedin.com/company/cloudmersive)
- [Website](https://cloudmersive.com/)
- [Portal](https://cloudmersive.com/developer)
- [A P I  Console](https://api-console.cloudmersive.com/swagger/index.html)
- [Open A P I  Index](https://api.cloudmersive.com/openapi.asp)
- [Privacy Policy](https://cloudmersive.com/privacy-policy)
- [JSON-LD](json-ld/cloudmersive-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/cloudmersive-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
