	
# Synthox Platform
# SynthoX – Synthetic Data Marketplace
> **The data you need. None of the risk you don’t.**

**Vision**
To become the global, decentralized infrastructure for training AI safely—where every developer accesses high-quality data without compromising privacy.

**Mission**
Empower innovation with custom, synthetic data that’s fully compliant, trustlessly verifiable, and 99% cheaper than real-world datasets.

> **The data you need. Without the risks you don't.**

<!-- SynthoX ASCII Logo -->
<pre style="font-family: 'Courier New', monospace; line-height:1.2;">
<span style="color:#1E3A8A;"> ____ _ _ ___ </span>
<span style="color:#1E3A8A;"> / ___| _ _ _ __ | |_| |__ ___ / _ \ </span>
<span style="color:#10B981;"> \___ \| | | | '_ \| __| '_ \ / _ \ (_) |</span>
<span style="color:#10B981;"> ___) | |_| | | | | |_| | | | (_) \__, |</span>
<span style="color:#1E3A8A;"> |____/ \__, |_| |_|\__|_| |_|\___/ /_/ </span>
<span style="color:#1E3A8A;"> |___/ </span>
<span style="color:#F3F4F6;"> <strong>Synthetic Data Exchange</strong></span>
</pre>



## Tech Stack
- Frontend: React + Tailwind
- Backend: FastAPI (Python)
- Blockchain: Solidity + Polygon
- AI: CTGAN + Grok API
- Storage: IPFS
## Why Synthox?

| Problem | Synthox Solution |
|------------------------------------|---------------------------------------------|
| Real data = privacy risk, legal cost | Synthetic data = zero PII, full compliance |
| Data access limited to big tech | Open marketplace for all developers |
| High cost + slow procurement | Instant, on-demand generation |

### Architecture
```mermaid
graph TD
A[User Wallet<br>MetaMask] --> B[Frontend<br>React + Tailwind]
B --> C[Backend API<br>FastAPI]
C --> D[Smart Contract<br>Solidity on Polygon]
C --> E[AI Data Generator<br>CTGAN + Grok]
E --> F[IPFS Storage]
D -->|USDC Payment| C
F -->|Download Link| B
B -->|Compliance PDF| A

style A fill:#1E3A8A, color:white
style B fill:#10B981, color:white
style C fill:#F3F4F6, color:black
style D fill:#1E3A8A, color:white
style E fill:#10B981, color:white
style F fill:#F3F4F6, color:black

### Database Schema

- `users` – Wallet-based identity
- `domains` – Data categories (medical, finance, retail)
- `requests` – All generation jobs
- `generated_files` – Output + compliance reports
- `price_tiers` – Dynamic pricing per row

Full SQL in [`database/schema.sql`](./database/schema.sql)

### First Demo Dataset

- **Domain**: Medical
- **Use Case**: Diabetes prediction
- Sample: [`datasets/diabetes_sample.csv`](./datasets/diabetes_sample.csv)

### Week 2 Checklist

| Task | Status |
|------|--------|
| Architecture diagram (Mermaid) | ✅ Done |
| Full PostgreSQL schema | ✅ Done |
| First demo dataset | ✅ Done |
| README updated | ✅ Done |