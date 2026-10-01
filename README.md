# Onkar Nagargoje — GitHub Profile & SOC Portfolio

Personalized, recruiter-ready GitHub assets for **Onkar Nagargoje** — dual-degree **CSE + Cyber Security & Digital Forensics** student targeting **SOC Analyst**, blue-team, network security, and IT support roles.

## Deploy in 5 minutes

| Step | Action |
|------|--------|
| 1 | Create GitHub repo **`Onkar-Nagargoje`** (same as your username) |
| 2 | Copy everything from [`profile/`](profile/) into that repo (README + `.github/workflows/snake.yml`) |
| 3 | Push [`projects/firewall-log-analyzer`](projects/firewall-log-analyzer) to **`firewall-log-analyzer`** and **pin** it on your profile |
| 4 | Paste bio from [`profile/GITHUB_SETTINGS.md`](profile/GITHUB_SETTINGS.md) into GitHub settings |
| 5 | Run through [`docs/RECRUITER_CHECKLIST.md`](docs/RECRUITER_CHECKLIST.md) |

Detailed steps (English + Hindi): [`docs/GITHUB_DEPLOY.md`](docs/GITHUB_DEPLOY.md)

## Highlights

- **`profile/README.md`** — Designed profile README: SOC section, mermaid SOC flow, projects from your resume, stats, typing header, skill icons  
- **`profile/GITHUB_SETTINGS.md`** — Ready-made GitHub bio mentioning **SOC**  
- **`projects/firewall-log-analyzer`** — Pin-worthy Python CLI (log triage + MITRE hints)  
- **`docs/lab-writeup-template.md`** — THM/HTB/homelab reports for recruiters  

## Run the SOC demo tool

```bash
cd projects/firewall-log-analyzer
pip install -e ".[dev]"
export PATH="$HOME/.local/bin:$PATH"
firewall-analyzer analyze sample_logs/firewall.log --top 10
pytest -q
```

## Contact

**Onkar Nagargoje** · onkarnagargoje25@gmail.com · [LinkedIn](https://www.linkedin.com/in/Onkar-Nagargoje-836797291) · [Portfolio](https://nagargojeonkar.netlify.app/)
