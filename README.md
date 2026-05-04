# 🛡️ Xia0checkmate | Architectural Logic Decoder
> **Application Security Researcher | Security Philosopher | Author & R&D Specialist**

---

### 👤 Intel: The Logic Decoder
A high-precision security researcher driven by the belief that automation inherently misses the nuance of architecture. My methodology prioritizes **Manual Precision** over automated noise, identifying deep-seated logic flaws that standard scanners overlook.

*   **🏆 Global Ranking:** Ranked **#2** in Jordan (VDP 2026) on the **HackerOne** platform.
*   **🏅 Hall of Fame:** Ranked **#57** in the official **Vodafone** Hall of Fame.
*   **🧪 R&D:** Creator of **AlgOrigin**, a high-performance Go-based engine designed for infrastructure subversion and WAF bypassing.

---

### 📊 Vital Statistics
| Achievement | Status |
| :--- | :--- |
| **HackerOne Rank (Jordan)** | `#2` (VDP 2026) |
| **Private Invitations** | `70+` (Acquired within month one) |
| **TryHackMe Global Rank** | `Top 6%` |
| **Methodology** | `Manual Precision Research` |

---

### 🎯 Primary Research Domains
Focused on identifying structural and behavioral discrepancies within high-scale production environments:

- [x] **Business Logic Abuse:** Exploiting architectural flaws in application workflows.
- [x] **Auth Subversion:** Manual exploitation of IDORs, session hijacking, and Auth bypasses.
- [x] **Infrastructure Hacking:** Origin IP discovery and WAF subversion.
- [x] **Race Conditions:** Exploiting temporal discrepancies in data processing.

---

### 🛠️ Featured Lab Project: `AlgOrigin.go`
An advanced reconnaissance engine written in **Go**, engineered to subvert modern WAF protections (Cloudflare, Akamai) through architectural analysis:

*   **DNS History Analysis:** Reconstructing historical A-records to identify origin leakage.
*   **IP Collection & Scrubbing:** Massive-scale IP vector collection and infrastructure mapping.
*   **ASN + IP Prefix Filtering:** Analyzing routing paths to uncover unprotected entry points.

```go
// core/logic: Searching for leaked origin IP
func TriggerBypass(target string) {
    AnalyzeHistoricalDNS(target)
    CollectInfrastructureAssets(target)
    ExecuteSubversionStrategy()
}
