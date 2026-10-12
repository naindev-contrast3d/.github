# Security Policy

At **Contrast3D & NainDev**, security, deterministic data integrity, and strict confidentiality are foundational to our engineering operations. We welcome responsible security reports regarding any vulnerability in our public or private systems.

---

### Supported Products & Systems

| System | Role | Status |
| :--- | :--- | :--- |
| **ContrastViewer** | Interactive 3D web component (`<contrast-vehicle-viewer>`) | Supported |
| **DSE (Datum Statutum Exploratum)** | Conformance chassis, validation API and MCP servers | Supported |
| **ContrastHub** | Collaborative CRM platform and client services | Supported |
| **Infrastructure & Edges** | Production host nodes (`NODE02`), tunnels, and CI gates | Supported |

---

### Reporting a Vulnerability

If you discover a potential security vulnerability in any repository, public endpoint, or service operated by Contrast3D & NainDev:

1. **Do not disclose publicly:** Please refrain from opening public GitHub issues, discussions, or pull requests regarding suspected security flaws.
2. **Contact via email:** Submit a detailed report directly to:
   - **Email:** `amendoza@contrast3d.com`
3. **Include the following information:**
   - Affected system, repository, or endpoint URL.
   - Severity assessment and vector explanation.
   - Step-by-step reproduction steps or proof-of-concept (PoC).
   - Any proposed remediation if known.

---

### Response & Remediation Timeline

- **Acknowledgement:** We acknowledge receipt of vulnerability reports within **48 hours**.
- **Assessment:** We conduct technical triage and determine impact within **5 business days**.
- **Fix & Deployment:** Critical vulnerabilities are prioritized through our local isolated CI pipelines and deployed directly to production nodes upon verification.
- **Credit:** We acknowledge security researchers who adhere to responsible disclosure principles.
