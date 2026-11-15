# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-hubspot-call-transcription-action-item-assigner`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes missed, duplicated, misassigned or incorrectly dated tasks, and any commercial consequence of acting on, or failing to act on, an AI-generated task.
* **No Warranty:** All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.
* **AI Output Is Not Authoritative:** Large language models can misread, omit or invent information. The validation layer reduces this risk but cannot remove it. Every AI-generated task must be treated as a suggestion and checked against the call recording by a person.
* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live HubSpot or OpenAI credentials. Treat every created task as a live change: it notifies the assignee and appears on customer records.
* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA), and security policies of HubSpot, OpenAI and any connected services. That includes obtaining any consent required to record and transcribe calls, confirming a lawful basis for sending transcript content to an AI provider, reviewing your provider's data-retention and training settings, applying appropriate retention to n8n execution logs, and honouring data-subject requests across every system the transcript passes through.
* **PII Redaction Is Best-Effort:** The built-in redaction masks common email, phone and card-number patterns only. It is not a data-loss-prevention system and will not catch every form of personal or sensitive data.

---

## Open-Source License Notice

This project is released under the MIT License.

```
MIT License

Copyright (c) 2026 DH Robin (dhRobin Systems)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Trademarks

HubSpot is a trademark of HubSpot, Inc. OpenAI and GPT are trademarks of OpenAI OpCo, LLC. n8n is a trademark of n8n GmbH. This project is independent and is not affiliated with, endorsed by, or sponsored by any of these companies.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
