<div align="center">
  <img src="https://capytoolkit.com/apple-touch-icon.png" width="100" height="100" alt="CapyToolkit">

  <h1>CapyToolkit</h1>

  <p>Most browser tools send your data to a server. These don't.</p>

  <p>
    Browser-based utility tools for developers, hardware diagnostics, and security work.<br>
    Everything runs client-side. No uploads, no accounts.
  </p>

  <p>
    <strong><a href="https://capytoolkit.com">capytoolkit.com</a></strong> &nbsp;·&nbsp;
    <a href="https://capytoolkit.com/blog/">Blog</a>
  </p>

  <p>
    <a href="https://github.com/capytoolkit"><img src="https://img.shields.io/badge/GitHub-capytoolkit-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
    &nbsp;
    <a href="https://x.com/CapyToolkit"><img src="https://img.shields.io/badge/X-CapyToolkit-000000?style=flat-square&logo=x&logoColor=white" alt="X"></a>
    &nbsp;
    <a href="https://bsky.app/profile/capytoolkit.com"><img src="https://img.shields.io/badge/Bluesky-capytoolkit.com-0285FF?style=flat-square&logo=bluesky&logoColor=white" alt="Bluesky"></a>
  </p>

  <a href="https://buymeacoffee.com/capytoolkit">
    <img src="https://img.buymeacoffee.com/button-api/?text=Buy+me+a+watermelon&emoji=%F0%9F%8D%89&slug=capytoolkit&button_colour=FFDD00&font_colour=000000&font_family=Lato&outline_colour=000000&coffee_colour=FFFFFF" alt="Buy me a watermelon">
  </a>

</div>

---

## Tools

### Hardware & Display Diagnostics

<table>
<thead>
<tr>
<th width="38%">Tool</th>
<th width="62%">Description</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/hardware/monitor-test/">Monitor & Display Test Suite</a></td><td>Dead pixel patterns, backlight bleed, motion ghosting, fullscreen test modes</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/input-lag/">Input Lag & Mouse Polling Rate Tester</a></td><td>Browser input latency and mouse polling rate via PointerEvent API</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/webcam-latency/">Webcam A/V Sync & Latency Meter</a></td><td>Millisecond offset between webcam and microphone, OBS-ready output</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/webcam-test/">Webcam Lighting & Framing Analyzer</a></td><td>Lighting balance, face framing, and resolution diagnostics</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/midi-test/">Web MIDI Keyboard & Latency Tester</a></td><td>Dead keys, ghost notes, and USB-to-browser MIDI input latency</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/gamepad-test/">Gamepad & Joystick Drift Tester</a></td><td>Analog stick drift, dead zone visualization, button diagnostics</td></tr>
<tr><td>Live Signal Debugger <em>(coming)</em></td><td>Real-time USB/Serial/Bluetooth signals from Arduino, sensors, MIDI controllers</td></tr>
<tr><td>WebUSB Hardware Flasher <em>(coming)</em></td><td>Flash firmware to ESP32, Arduino, and Raspberry Pi Pico in-browser</td></tr>
</tbody>
</table>

### Developer Parsers & Encoders

<table>
<thead>
<tr>
<th width="38%">Tool</th>
<th width="62%">Description</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/developer/jwt-decoder/">JWT Decoder</a></td><td>Inspect header, payload, and expiry of any JWT token</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/base64/">Base64 Encoder / Decoder</a></td><td>Encode and decode text or files to Base64</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/hash-generator/">Hash Generator</a></td><td>MD5, SHA-1, SHA-256, SHA-512, and HMAC computation</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/cron-parser/">Cron Expression Parser</a></td><td>Translate cron syntax to plain English with next-run preview</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/sql-workbench/">SQL Data Workbench</a></td><td>Query local files with SQL: Parquet, Arrow, Feather, Avro, DBF, Excel, CSV, JSON</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/log-explorer/">Big Log Explorer</a></td><td>Filter, search, and graph 500 MB+ log and JSONL files via Web Workers and IndexedDB</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/token-counter/">Prompt Token Counter</a></td><td>Token count and context window usage for GPT-4o, Claude, and Gemini models</td></tr>
<tr><td>JSON Formatter & Validator <em>(coming)</em></td><td>Pretty-print, minify, and validate JSON with syntax highlighting</td></tr>
<tr><td>Regex Tester <em>(coming)</em></td><td>Live match highlighting and group capture view</td></tr>
<tr><td>UUID Generator <em>(coming)</em></td><td>Cryptographically random UUID v4 with bulk export</td></tr>
<tr><td>Text / Code Diff Viewer <em>(coming)</em></td><td>Side-by-side and unified diff with line-level highlighting</td></tr>
<tr><td>Binary Package Differ <em>(coming)</em></td><td>Diff two ZIP archives or build artifacts: file tree, size delta, byte-level changes</td></tr>
<tr><td>WASM Binary Inspector <em>(coming)</em></td><td>Decompile WebAssembly to WAT, memory map, exports and imports</td></tr>
</tbody>
</table>

### Security & Privacy Tools

<table>
<thead>
<tr>
<th width="38%">Tool</th>
<th width="62%">Description</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/security/browser-fingerprint/">Browser Fingerprint Inspector</a></td><td>Canvas hash, WebGL renderer, audio fingerprint, fonts, and 30+ leak signals</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/pii-scrubber/">PII Scrubber</a></td><td>Detect and tokenize PII, secrets, and internal data before sending to AI</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/exif-scrubber/">EXIF & Image Metadata Scrubber</a></td><td>Strip GPS coordinates, timestamps, and device data from images</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/ocr-redactor/">Offline OCR & Document Redactor</a></td><td>Extract text and redact sensitive regions via Tesseract WASM</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/cert-inspector/">X.509 Certificate Inspector</a></td><td>Validity, SANs, key algorithm, chain depth, and expiry from PEM or DER input</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/config-sanitizer/">Cloud Config Sanitizer</a></td><td>Validate Kubernetes, Terraform, and YAML manifests, detect secrets and security smells</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/hash-verifier/">File Hash Verifier</a></td><td>SHA-256, SHA-512, SHA-1, and MD5 checksums compared against a published hash</td></tr>
<tr><td>Password Entropy Analyser <em>(coming)</em></td><td>Bits of entropy and estimated crack time</td></tr>
<tr><td>URL Encoder / Decoder <em>(coming)</em></td><td>Percent-encode and decode URLs and query strings with component parsing</td></tr>
<tr><td>Quantum-Safe Encryptor <em>(coming)</em></td><td>Post-quantum encryption and decryption via Kyber/Dilithium WASM</td></tr>
<tr><td>Build Integrity Verifier <em>(coming)</em></td><td>SHA-256 and BLAKE3 artifact comparison with functional content diff</td></tr>
<tr><td>Local Secret Scanner <em>(coming)</em></td><td>Scan code, configs, and ZIP archives for API keys, tokens, and credentials</td></tr>
</tbody>
</table>

### Audio & Acoustic Testing

<table>
<thead>
<tr>
<th width="38%">Tool</th>
<th width="62%">Description</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/audio/speaker-sweep/">Speaker Frequency Sweep & Resonance Tester</a></td><td>20 Hz to 20 kHz sweep to find resonances, rattle points, and drop-off frequencies</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/audio/mic-test/">Microphone Quality, Noise & Latency Tester</a></td><td>Noise floor, clipping, frequency response, echo loopback, and round-trip latency</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/audio/decibel-calc/">Decibel Calculator</a></td><td>Convert between dB, watts, volts, and SPL with formula reference</td></tr>
</tbody>
</table>

### Math & Engineering Calculators

<table>
<thead>
<tr>
<th width="38%">Tool</th>
<th width="62%">Description</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/math/ohms-law/">Ohm's Law Calculator</a></td><td>Solve for voltage, current, resistance, or power from any two values</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/math/resistor-calc/">Resistor Colour Code Calculator</a></td><td>4-band, 5-band, and 6-band decoding with tolerance, temperature coefficient, E-series</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/math/engineering-unit-converter/">Engineering Unit Converter</a></td><td>SI and imperial units across 17 physical dimensions</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/math/electricity-unit-converter/">Electricity Unit Converter</a></td><td>Charge, current, voltage, resistance, capacitance, inductance across 15 dimensions</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/math/aspect-ratio/">Aspect Ratio Calculator</a></td><td>Display resolutions, scaling, and letterbox bars for any ratio</td></tr>
</tbody>
</table>

### Text Analysis & Converters

<table>
<thead>
<tr>
<th width="38%">Tool</th>
<th width="62%">Description</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/text/readability-score/">Readability Analyser</a></td><td>Flesch-Kincaid Grade, Flesch Reading Ease, and SMOG with sentence-level highlights</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/text/case-converter/">Case Converter</a></td><td>camelCase, snake_case, SCREAMING_SNAKE, kebab-case, Title Case, PascalCase</td></tr>
<tr><td>Reading Time Calculator <em>(coming)</em></td><td>Reading time estimate at adjustable WPM targets</td></tr>
<tr><td>Markdown Preview <em>(coming)</em></td><td>Live-render Markdown with clean typeset output and copy-as-HTML export</td></tr>
</tbody>
</table>

### Web Design Utilities & CSS Tools

<table>
<thead>
<tr>
<th width="38%">Tool</th>
<th width="62%">Description</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/design/color-converter/">Color Format Converter</a></td><td>Convert between HEX, RGB, HSL, HSV, OKLCH, and CSS named colours</td></tr>
<tr><td>WCAG Contrast Checker <em>(coming)</em></td><td>AA and AAA contrast ratio testing with hex, RGB, and HSL input</td></tr>
<tr><td>CSS Gradient Builder <em>(coming)</em></td><td>Visual linear and radial gradient editor with live CSS output</td></tr>
</tbody>
</table>

### Network & Web Reference Tools

<table>
<thead>
<tr>
<th width="38%">Tool</th>
<th width="62%">Description</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/network/subnet-calculator/">IPv4 / IPv6 Subnet & CIDR Calculator</a></td><td>Network ranges, broadcast addresses, and host counts for IPv4 and IPv6</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/url-parser/">URL Parser & Inspector</a></td><td>Decompose any URL into protocol, host, path, query params, and fragment</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/http-status/">HTTP Status Code Reference</a></td><td>Searchable reference for all HTTP 1xx to 5xx codes with usage notes</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/p2p-tester/">P2P Network Tester</a></td><td>WebRTC peer-to-peer latency, jitter, and packet loss between two browsers</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/indexnow-submitter/">IndexNow URL Submitter</a></td><td>Submit URLs to Bing, Yandex, Naver, and more via IndexNow</td></tr>
<tr><td>MIME Type Reference <em>(coming)</em></td><td>Searchable MIME database with extension mapping and RFC sources</td></tr>
</tbody>
</table>

---

## Recent posts

- [Debugging 500 MB+ Application Logs in the Browser Without Uploading](https://capytoolkit.com/blog/developer-tools/debugging-500-mb-application-logs-in-the-browser-without-uploading/)
- [Counting Prompt Tokens Locally Before Sending to GPT, Claude, and Gemini](https://capytoolkit.com/blog/developer-tools/counting-prompt-tokens-locally-gpt-claude-gemini/)
- [Debugging and Exploring Parquet Files with Local SQL Queries](https://capytoolkit.com/blog/developer-tools/debugging-and-exploring-parquet-files-with-local-sql-queries/)
- [Testing WebRTC Peer-to-Peer Connection Quality Without Cloud Relay Servers](https://capytoolkit.com/blog/developer-tools/testing-webrtc-peer-peer-connection-quality-cloud-relay-servers/)
- [Home Studio Decibel Calibration: Accurate SPL Measurement and Noise Floor Analysis Without Uploads](https://capytoolkit.com/blog/audio/home-studio-decibel-calibration-spl-measurement-noise-floor-analysis/)

---

Built with [Astro](https://astro.build) and TypeScript. Installable as a PWA.
