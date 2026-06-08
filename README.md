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
    <a href="https://www.reddit.com/user/CapyToolkit/"><img src="https://img.shields.io/badge/Reddit-CapyToolkit-FF4500?style=flat-square&logo=reddit&logoColor=white" alt="Reddit"></a>
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
<th width="33%">Tool</th>
<th width="47%">Description</th>
<th width="20%">Release date</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/hardware/monitor-test/">Monitor & Display Test Suite</a></td><td>Dead pixel patterns, backlight bleed, motion ghosting, fullscreen test modes</td><td>2026-04-15</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/input-lag/">Input Lag & Mouse Polling Rate Tester</a></td><td>Browser input latency and mouse polling rate via PointerEvent API</td><td>2026-04-23</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/webcam-latency/">Webcam A/V Sync & Latency Meter</a></td><td>Millisecond offset between webcam and microphone, OBS-ready output</td><td>2026-05-20</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/webcam-test/">Webcam Lighting & Framing Analyzer</a></td><td>Lighting balance, face framing, and resolution diagnostics</td><td>2026-04-22</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/midi-test/">Web MIDI Keyboard & Latency Tester</a></td><td>Dead keys, ghost notes, and USB-to-browser MIDI input latency</td><td>2026-04-24</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/hardware/gamepad-test/">Gamepad & Joystick Drift Tester</a></td><td>Analog stick drift, dead zone visualization, button diagnostics</td><td>2026-04-30</td></tr>
<tr><td>Live Signal Debugger <em>(coming)</em></td><td>Real-time USB/Serial/Bluetooth signals from Arduino, sensors, MIDI controllers</td><td>2026-06*</td></tr>
<tr><td>WebUSB Hardware Flasher <em>(coming)</em></td><td>Flash firmware to ESP32, Arduino, and Raspberry Pi Pico in-browser</td><td>2026-07*</td></tr>
</tbody>
</table>

### Developer Parsers & Encoders

<table>
<thead>
<tr>
<th width="33%">Tool</th>
<th width="47%">Description</th>
<th width="20%">Release date</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/developer/jwt-decoder/">JWT Decoder</a></td><td>Inspect header, payload, and expiry of any JWT token</td><td>2026-04-23</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/cron-parser/">Cron Expression Parser</a></td><td>Translate cron syntax to plain English with next-run preview</td><td>2026-04-25</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/base64/">Base64 Encoder / Decoder</a></td><td>Encode and decode text or files to Base64</td><td>2026-05-06</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/sql-workbench/">SQL Data Workbench</a></td><td>Query local files with SQL: Parquet, Arrow, Feather, Avro, DBF, Excel, CSV, JSON</td><td>2026-05-16</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/log-explorer/">Big Log Explorer</a></td><td>Filter, search, and graph 500 MB+ log and JSONL files via Web Workers and IndexedDB</td><td>2026-05-18</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/token-counter/">Prompt Token Counter</a></td><td>Token count and context window usage for GPT-4o, Claude, and Gemini models</td><td>2026-05-18</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/developer/hash-generator/">Hash Generator</a></td><td>MD5, SHA-1, SHA-256, SHA-512, and HMAC computation</td><td>2026-05-20</td></tr>
<tr><td>JSON Formatter & Validator <em>(coming)</em></td><td>Pretty-print, minify, and validate JSON with syntax highlighting</td><td>2026-06*</td></tr>
<tr><td>Regex Tester <em>(coming)</em></td><td>Live match highlighting and group capture view</td><td>2026-06*</td></tr>
<tr><td>UUID Generator <em>(coming)</em></td><td>Cryptographically random UUID v4 with bulk export</td><td>2026-06*</td></tr>
<tr><td>Text / Code Diff Viewer <em>(coming)</em></td><td>Side-by-side and unified diff with line-level highlighting</td><td>2026-07*</td></tr>
<tr><td>Binary Package Differ <em>(coming)</em></td><td>Diff two ZIP archives or build artifacts: file tree, size delta, byte-level changes</td><td>2026-07*</td></tr>
<tr><td>WASM Binary Inspector <em>(coming)</em></td><td>Decompile WebAssembly to WAT, memory map, exports and imports</td><td>2026-07*</td></tr>
</tbody>
</table>

### Security & Privacy Tools

<table>
<thead>
<tr>
<th width="33%">Tool</th>
<th width="47%">Description</th>
<th width="20%">Release date</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/security/hash-verifier/">File Hash Verifier</a></td><td>SHA-256, SHA-512, SHA-1, and MD5 checksums compared against a published hash</td><td>2026-04-23</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/exif-scrubber/">EXIF & Image Metadata Scrubber</a></td><td>Strip GPS coordinates, timestamps, and device data from images</td><td>2026-04-23</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/browser-fingerprint/">Browser Fingerprint Inspector</a></td><td>Canvas hash, WebGL renderer, audio fingerprint, fonts, and 30+ leak signals</td><td>2026-05-04</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/pii-scrubber/">PII Scrubber</a></td><td>Detect and tokenize PII, secrets, and internal data before sending to AI</td><td>2026-05-08</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/ocr-redactor/">Offline OCR & Document Redactor</a></td><td>Extract text and redact sensitive regions via Tesseract WASM</td><td>2026-05-13</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/cert-inspector/">X.509 Certificate Inspector</a></td><td>Validity, SANs, key algorithm, chain depth, and expiry from PEM or DER input</td><td>2026-05-18</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/config-sanitizer/">Cloud Config Sanitizer</a></td><td>Validate Kubernetes, Terraform, and YAML manifests, detect secrets and security smells</td><td>2026-05-19</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/security/url-encoder/">URL Encoder / Decoder</a></td><td>Percent-encode and decode URLs and query strings with component parsing</td><td>2026-06-06</td></tr>
<tr><td>Password Entropy Analyser <em>(coming)</em></td><td>Bits of entropy and estimated crack time</td><td>2026-06*</td></tr>
<tr><td>Quantum-Safe Encryptor <em>(coming)</em></td><td>Post-quantum encryption and decryption via Kyber/Dilithium WASM</td><td>2026-07*</td></tr>
<tr><td>Build Integrity Verifier <em>(coming)</em></td><td>SHA-256 and BLAKE3 artifact comparison with functional content diff</td><td>2026-07*</td></tr>
<tr><td>Local Secret Scanner <em>(coming)</em></td><td>Scan code, configs, and ZIP archives for API keys, tokens, and credentials</td><td>2026-07*</td></tr>
</tbody>
</table>

### Audio & Acoustic Testing

<table>
<thead>
<tr>
<th width="33%">Tool</th>
<th width="47%">Description</th>
<th width="20%">Release date</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/audio/mic-test/">Microphone Quality, Noise & Latency Tester</a></td><td>Noise floor, clipping, frequency response, echo loopback, and round-trip latency</td><td>2026-04-22</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/audio/speaker-sweep/">Speaker Frequency Sweep & Resonance Tester</a></td><td>20 Hz to 20 kHz sweep to find resonances, rattle points, and drop-off frequencies</td><td>2026-04-24</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/audio/decibel-calc/">Decibel Calculator</a></td><td>Convert between dB, watts, volts, and SPL with formula reference</td><td>2026-05-08</td></tr>
</tbody>
</table>

### Math & Engineering Calculators

<table>
<thead>
<tr>
<th width="33%">Tool</th>
<th width="47%">Description</th>
<th width="20%">Release date</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/math/resistor-calc/">Resistor Colour Code Calculator</a></td><td>4-band, 5-band, and 6-band decoding with tolerance, temperature coefficient, E-series</td><td>2026-04-24</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/math/engineering-unit-converter/">Engineering Unit Converter</a></td><td>SI and imperial units across 17 physical dimensions</td><td>2026-05-02</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/math/electricity-unit-converter/">Electricity Unit Converter</a></td><td>Charge, current, voltage, resistance, capacitance, inductance across 15 dimensions</td><td>2026-05-02</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/math/ohms-law/">Ohm's Law Calculator</a></td><td>Solve for voltage, current, resistance, or power from any two values</td><td>2026-05-07</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/math/aspect-ratio/">Aspect Ratio Calculator</a></td><td>Display resolutions, scaling, and letterbox bars for any ratio</td><td>2026-05-07</td></tr>
</tbody>
</table>

### Text Analysis & Converters

<table>
<thead>
<tr>
<th width="33%">Tool</th>
<th width="47%">Description</th>
<th width="20%">Release date</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/text/readability-score/">Readability Analyser</a></td><td>Flesch-Kincaid Grade, Flesch Reading Ease, and SMOG with sentence-level highlights</td><td>2026-04-27</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/text/case-converter/">Case Converter</a></td><td>camelCase, snake_case, SCREAMING_SNAKE, kebab-case, Title Case, PascalCase</td><td>2026-05-07</td></tr>
<tr><td>Reading Time Calculator <em>(coming)</em></td><td>Reading time estimate at adjustable WPM targets</td><td>2026-06*</td></tr>
<tr><td>Markdown Preview <em>(coming)</em></td><td>Live-render Markdown with clean typeset output and copy-as-HTML export</td><td>2026-06*</td></tr>
</tbody>
</table>

### Web Design Utilities & CSS Tools

<table>
<thead>
<tr>
<th width="33%">Tool</th>
<th width="47%">Description</th>
<th width="20%">Release date</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/design/color-converter/">Color Format Converter</a></td><td>Convert between HEX, RGB, HSL, HSV, OKLCH, and CSS named colours</td><td>2026-05-01</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/design/gradient-builder/">CSS Gradient Builder</a></td><td>Visual linear, radial, and conic gradient editor with live CSS output</td><td>2026-06-07</td></tr>
<tr><td>WCAG Contrast Checker <em>(coming)</em></td><td>AA and AAA contrast ratio testing with hex, RGB, and HSL input</td><td>2026-06*</td></tr>
</tbody>
</table>

### Network & Web Reference Tools

<table>
<thead>
<tr>
<th width="33%">Tool</th>
<th width="47%">Description</th>
<th width="20%">Release date</th>
</tr>
</thead>
<tbody>
<tr><td><a href="https://capytoolkit.com/tools/network/subnet-calculator/">IPv4 / IPv6 Subnet & CIDR Calculator</a></td><td>Network ranges, broadcast addresses, and host counts for IPv4 and IPv6</td><td>2026-05-06</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/url-parser/">URL Parser & Inspector</a></td><td>Decompose any URL into protocol, host, path, query params, and fragment</td><td>2026-05-03</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/p2p-tester/">P2P Network Tester</a></td><td>WebRTC peer-to-peer latency, jitter, and packet loss between two browsers</td><td>2026-05-13</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/indexnow-submitter/">IndexNow URL Submitter</a></td><td>Submit URLs to Bing, Yandex, Naver, and more via IndexNow</td><td>2026-05-23</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/mime-reference/">MIME Type Reference</a></td><td>Searchable MIME database with extension mapping and RFC sources</td><td>2026-05-31</td></tr>
<tr><td><a href="https://capytoolkit.com/tools/network/http-status/">HTTP Status Code Reference</a></td><td>Searchable reference for all HTTP 1xx to 5xx codes with usage notes</td><td>2026-05-20</td></tr>
</tbody>
</table>

<sub>* Planned release</sub>

---

## Recent posts

- [Build CSS Gradients Visually Without Sending Design Data to a Server](https://capytoolkit.com/blog/guides/build-css-gradients-visually-without-sending-design-data-to-a-server/)
- [Percent-Encoding Rules Every API Developer Should Know, and When to Apply Them](https://capytoolkit.com/blog/security-privacy/url-encoder-decoder-capytoolkit-what-it-does-who-needs-it/)
- [Network Diagnostics Without Cloud APIs: Subnet Planning, P2P Testing, and URL Inspection](https://capytoolkit.com/blog/guides/network-diagnostics-subnet-planning-p2p-testing-url-inspection/)
- [Ohm's Law: Solving for Voltage, Current, and Resistance Without a Scientific Calculator](https://capytoolkit.com/blog/guides/ohms-law-solve-voltage-current-resistance-online/)
- [Choosing an AI Model Based on Token Pricing and Context Window Fit](https://capytoolkit.com/blog/buying-guides/choosing-an-ai-model-based-on-token-pricing-and-context-window-fit/)
- [How Java Developers Use Client-Side Case Conversion for Clean Code and Configuration Files](https://capytoolkit.com/blog/developer-tools/java-developers-use-client-side-case-conversion-clean-code-configuration-files/)

---

Built with [Astro](https://astro.build) and TypeScript. Installable as a PWA.
