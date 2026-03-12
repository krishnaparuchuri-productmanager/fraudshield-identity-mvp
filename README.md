# FraudShield: AI Identity Fraud Checker MVP 🔒

## Problem
**In India, digital fraud costs ₹1.25L Cr/year (RBI). Users fear fake KYC in apps (loans, UPI). No simple self-check tool for "is this identity safe?"**

- Users: Consumers (20-40yo urban), small biz owners verifying partners.
- Pains: Tedious manual checks; no quick AI risk score.
- Opportunity: 500M+ Aadhaar-linked users; post-2025 data laws demand better tools.

## Solution
No-code MVP: Input phone/email/Aadhaar snippet → **AI/ML-powered risk score + prevention tips**. Built for speed/privacy.

**Live Demo:** [Notion]
((https://www.notion.so/Fraud-Identity-Scans-31eda61263cf80bd84c1cbe8a94c7038?source=copy_link))

## Features
1. **AI Risk Scanner** (GPT + ML): Flags high-risk patterns (temp email, fraud signals).
2. **Privacy-First KYC Simulator**: Mock verification without real data. 
3. **Report Generator**: Shareable PDF with score/advice.

## AI/ML Under the Hood
- **NLP Fraud Classifier:** OpenAI GPT-4o-mini (fine-prompted on RBI fraud patterns).
- **Anomaly Detection:** Rule-based + ML (Teachable Machine prototype). 
- **Accuracy:** 82% on 50 test cases (manual eval).
- **Privacy:** No data stored; edge-processed.

## Process

### Discovery
- Polled 10 Hyderabad friends/fintech LinkedIn: 70% hit fraud; want proactive tool.
- Teardown: Truecaller (contacts-only), govt portals (slow) → gap for personal AI.

### Build
- **Stack:** Glide (app UI), GPT (analysis), Google Sheets (DB), Zapier (AI pipeline).
- **Tradeoffs:**
  | Tool | Pros | Cons | Pick |
  |------|------|------|------|
  | Bubble | Full app | Complex | No |
  | Glide | Mobile-first, fast | Sheet limits | Yes |
  | Code | Accurate ML | Non-tech | No |

### Metrics & Next
- **Test:** 20 users → 85% accuracy on mocks; NPS 8/10.
- **v2:** Real API (Onfido?), UPI fraud alerts, ML model training.

## Artifacts
- [User Interviews](`docs/interviews.md`)
- [Sample AI Report](`docs/docs/docs/sample-report.md)
- [Glide Template](https://glide.link/your-template)
- [Test Cases + Accuracy Log](`docs/docs/accuracy.md)

---

Built by **[Paruchuri Krishna Chowdari]**, PM | Fintech Fraud & AI Focus | Hyderabad  
📧 krishna1parchuri@gmail.com | 🔗 [LinkedIn](www.linkedin.com/in/paruchurikrishnachowdari)  
Open to feedback/PRs! ⭐
