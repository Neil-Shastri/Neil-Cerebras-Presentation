# Summer Internship Presentation — Cerebras Systems

**Neil Shastri** · Software Engineer Intern, Cluster Control Plane · May 2026 – Aug 2026

An interactive, browser-based slide deck covering my summer internship at Cerebras Systems: migrating cluster application deployment from imperative shell scripts to declarative GitOps with ArgoCD, using the Prometheus observability stack as the first (and hardest) app.

---

## ▶️ How to View the Presentation

1. **Download** `index.html` (open it above → ⬇ **Download raw file**).
2. **Right-click** (or **two-finger click** on Mac) the file → **Open With** → your browser.
3. Press **→** to advance and **N** for speaker notes.

**Exporting to PDF:** use your browser's **Print** (`Ctrl+P` / `Cmd+P`) → **Save as PDF**. Every slide prints on its own page with all elements shown.

---

## 💼 Internship Highlights

- **Re-architected cluster infrastructure** by replacing brittle PSSH/PSCP-based orchestration with a declarative, pull-based control plane using Kubernetes CRDs and node-level agents, enabling **15x cluster fleet scalability**.
- **Built GitOps-driven deployment infrastructure** with Argo CD, Helm, and Terraform to enable Infrastructure as Code and deterministic deployments across hundreds of air-gapped WSE-3 AI clusters.
- **Enhanced observability and platform reliability** using Prometheus, Thanos, VictoriaMetrics, and Grafana, maintaining **100% service availability** while improving alert response time by **over 2x**.

**Tech:** Kubernetes · Helm · Argo CD · ApplicationSets · Terraform · Prometheus · Thanos · VictoriaMetrics · Grafana · Alertmanager · Gateway API

---

## 🛠️ Built With

Plain HTML, CSS, and vanilla JavaScript in a single file — no frameworks, build step, or external dependencies. The color theme lives in one block at the top of the `<style>` section and is validated for contrast in both light and dark modes.

---

## 🙏 Acknowledgments

Thank you to [Agam Brahma](https://www.linkedin.com/in/agam-brahma/) and the larger Cerebras cluster software org for the mentorship and support this summer.
