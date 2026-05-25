# CapyToolkit

Browser-based utility tools for developers, hardware diagnostics, and security work.
Everything runs client-side. No uploads, no accounts.

**[capytoolkit.com](https://capytoolkit.com)** &nbsp;·&nbsp; [Blog](https://capytoolkit.com/blog/)

---

## Tools

### Hardware & Display Diagnostics

| Tool | Description |
|------|-------------|
| [Monitor & Display Test Suite](https://capytoolkit.com/tools/hardware/monitor-test/) | Dead pixel patterns, backlight bleed, motion ghosting, fullscreen test modes |
| [Input Lag & Mouse Polling Rate Tester](https://capytoolkit.com/tools/hardware/input-lag/) | Browser input latency and mouse polling rate via PointerEvent API |
| [Webcam A/V Sync & Latency Meter](https://capytoolkit.com/tools/hardware/webcam-latency/) | Millisecond offset between webcam and microphone, OBS-ready output |
| [Webcam Lighting & Framing Analyzer](https://capytoolkit.com/tools/hardware/webcam-test/) | Lighting balance, face framing, and resolution diagnostics |
| [Web MIDI Keyboard & Latency Tester](https://capytoolkit.com/tools/hardware/midi-test/) | Dead keys, ghost notes, and USB-to-browser MIDI input latency |
| [Gamepad & Joystick Drift Tester](https://capytoolkit.com/tools/hardware/gamepad-test/) | Analog stick drift, dead zone visualization, button diagnostics |
| Live Signal Debugger *(coming)* | Real-time USB/Serial/Bluetooth signals from Arduino, sensors, MIDI controllers |
| WebUSB Hardware Flasher *(coming)* | Flash firmware to ESP32, Arduino, and Raspberry Pi Pico in-browser |

### Developer Parsers & Encoders

| Tool | Description |
|------|-------------|
| [JWT Decoder](https://capytoolkit.com/tools/developer/jwt-decoder/) | Inspect header, payload, and expiry of any JWT token |
| [Base64 Encoder / Decoder](https://capytoolkit.com/tools/developer/base64/) | Encode and decode text or files to Base64 |
| [Hash Generator](https://capytoolkit.com/tools/developer/hash-generator/) | MD5, SHA-1, SHA-256, SHA-512, and HMAC computation |
| [Cron Expression Parser](https://capytoolkit.com/tools/developer/cron-parser/) | Translate cron syntax to plain English with next-run preview |
| [SQL Data Workbench](https://capytoolkit.com/tools/developer/sql-workbench/) | Query local files with SQL: Parquet, Arrow, Feather, Avro, DBF, Excel, CSV, JSON |
| [Big Log Explorer](https://capytoolkit.com/tools/developer/log-explorer/) | Filter, search, and graph 500 MB+ log and JSONL files via Web Workers and IndexedDB |
| [Prompt Token Counter](https://capytoolkit.com/tools/developer/token-counter/) | Token count and context window usage for GPT-4o, Claude, and Gemini models |
| JSON Formatter & Validator *(coming)* | Pretty-print, minify, and validate JSON with syntax highlighting |
| Regex Tester *(coming)* | Live match highlighting and group capture view |
| UUID Generator *(coming)* | Cryptographically random UUID v4 with bulk export |
| Text / Code Diff Viewer *(coming)* | Side-by-side and unified diff with line-level highlighting |
| Binary Package Differ *(coming)* | Diff two ZIP archives or build artifacts: file tree, size delta, byte-level changes |
| WASM Binary Inspector *(coming)* | Decompile WebAssembly to WAT, memory map, exports and imports |

### Security & Privacy Tools

| Tool | Description |
|------|-------------|
| [Browser Fingerprint Inspector](https://capytoolkit.com/tools/security/browser-fingerprint/) | Canvas hash, WebGL renderer, audio fingerprint, fonts, and 30+ leak signals |
| [PII Scrubber](https://capytoolkit.com/tools/security/pii-scrubber/) | Detect and tokenize PII, secrets, and internal data before sending to AI |
| [EXIF & Image Metadata Scrubber](https://capytoolkit.com/tools/security/exif-scrubber/) | Strip GPS coordinates, timestamps, and device data from images |
| [Offline OCR & Document Redactor](https://capytoolkit.com/tools/security/ocr-redactor/) | Extract text and redact sensitive regions via Tesseract WASM |
| [X.509 Certificate Inspector](https://capytoolkit.com/tools/security/cert-inspector/) | Validity, SANs, key algorithm, chain depth, and expiry from PEM or DER input |
| [Cloud Config Sanitizer](https://capytoolkit.com/tools/security/config-sanitizer/) | Validate Kubernetes, Terraform, and YAML manifests, detect secrets and security smells |
| [File Hash Verifier](https://capytoolkit.com/tools/security/hash-verifier/) | SHA-256, SHA-512, SHA-1, and MD5 checksums compared against a published hash |
| Password Entropy Analyser *(coming)* | Bits of entropy and estimated crack time |
| URL Encoder / Decoder *(coming)* | Percent-encode and decode URLs and query strings with component parsing |
| Quantum-Safe Encryptor *(coming)* | Post-quantum encryption and decryption via Kyber/Dilithium WASM |
| Build Integrity Verifier *(coming)* | SHA-256 and BLAKE3 artifact comparison with functional content diff |
| Local Secret Scanner *(coming)* | Scan code, configs, and ZIP archives for API keys, tokens, and credentials |

### Audio & Acoustic Testing

| Tool | Description |
|------|-------------|
| [Speaker Frequency Sweep & Resonance Tester](https://capytoolkit.com/tools/audio/speaker-sweep/) | 20 Hz to 20 kHz sweep to find resonances, rattle points, and drop-off frequencies |
| [Microphone Quality, Noise & Latency Tester](https://capytoolkit.com/tools/audio/mic-test/) | Noise floor, clipping, frequency response, echo loopback, and round-trip latency |
| [Decibel Calculator](https://capytoolkit.com/tools/audio/decibel-calc/) | Convert between dB, watts, volts, and SPL with formula reference |

### Math & Engineering Calculators

| Tool | Description |
|------|-------------|
| [Ohm's Law Calculator](https://capytoolkit.com/tools/math/ohms-law/) | Solve for voltage, current, resistance, or power from any two values |
| [Resistor Colour Code Calculator](https://capytoolkit.com/tools/math/resistor-calc/) | 4-band, 5-band, and 6-band decoding with tolerance, temperature coefficient, E-series |
| [Engineering Unit Converter](https://capytoolkit.com/tools/math/engineering-unit-converter/) | SI and imperial units across 17 physical dimensions |
| [Electricity Unit Converter](https://capytoolkit.com/tools/math/electricity-unit-converter/) | Charge, current, voltage, resistance, capacitance, inductance across 15 dimensions |
| [Aspect Ratio Calculator](https://capytoolkit.com/tools/math/aspect-ratio/) | Display resolutions, scaling, and letterbox bars for any ratio |

### Text Analysis & Converters

| Tool | Description |
|------|-------------|
| [Readability Analyser](https://capytoolkit.com/tools/text/readability-score/) | Flesch-Kincaid Grade, Flesch Reading Ease, and SMOG with sentence-level highlights |
| [Case Converter](https://capytoolkit.com/tools/text/case-converter/) | camelCase, snake_case, SCREAMING_SNAKE, kebab-case, Title Case, PascalCase |
| Reading Time Calculator *(coming)* | Reading time estimate at adjustable WPM targets |
| Markdown Preview *(coming)* | Live-render Markdown with clean typeset output and copy-as-HTML export |

### Web Design Utilities & CSS Tools

| Tool | Description |
|------|-------------|
| [Color Format Converter](https://capytoolkit.com/tools/design/color-converter/) | Convert between HEX, RGB, HSL, HSV, OKLCH, and CSS named colours |
| WCAG Contrast Checker *(coming)* | AA and AAA contrast ratio testing with hex, RGB, and HSL input |
| CSS Gradient Builder *(coming)* | Visual linear and radial gradient editor with live CSS output |

### Network & Web Reference Tools

| Tool | Description |
|------|-------------|
| [IPv4 / IPv6 Subnet & CIDR Calculator](https://capytoolkit.com/tools/network/subnet-calculator/) | Network ranges, broadcast addresses, and host counts for IPv4 and IPv6 |
| [URL Parser & Inspector](https://capytoolkit.com/tools/network/url-parser/) | Decompose any URL into protocol, host, path, query params, and fragment |
| [HTTP Status Code Reference](https://capytoolkit.com/tools/network/http-status/) | Searchable reference for all HTTP 1xx to 5xx codes with usage notes |
| [P2P Network Tester](https://capytoolkit.com/tools/network/p2p-tester/) | WebRTC peer-to-peer latency, jitter, and packet loss between two browsers |
| [IndexNow URL Submitter](https://capytoolkit.com/tools/network/indexnow-submitter/) | Submit URLs to Bing, Yandex, Naver, and more via IndexNow |
| MIME Type Reference *(coming)* | Searchable MIME database with extension mapping and RFC sources |

---

Built with [Astro](https://astro.build) and TypeScript. Installable as a PWA.
