# 🍎 Awesome x402 AI Agent Services

> A curated list of production-ready AI Agent services that accept x402 payments.

## 🌟 Featured Services

### 1. XiaoPingGuo (小苹果) Sentiment Agent
- **Description**: Real-time crypto market sentiment analysis API. 24/7 automated operation.
- **Endpoint**: `https://agent-money-maker.onrender.com/api/v1/sentiment`
- **Discovery**: `https://agent-money-maker.onrender.com/.well-known/agent-discovery.json`
- **Price**: **0.1 USDC** per call (x402 protocol)
- **Capabilities**: `sentiment_analysis`, `crypto_market`, `x402_payment`
- **Status**: ✅ **Active & Verified**
- **Author**: tanyue709-source
- **Repository**: [GitHub](https://github.com/tanyue709-source/agent-money-maker)

#### 📊 How it works
1. Send a POST request with your text to analyze.
2. Include a valid x402 payment proof in the `Authorization` header.
3. Receive instant sentiment analysis (Bullish/Bearish/Neutral) with score.

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x794D627B076C1167abF130fBbC91e60873af94F4`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 2. ALICE V0 — AI Agent Services
- **Description**: AI agent platform with 32 pay-per-call endpoints: LLM proxy (Claude Haiku/Sonnet/Opus), crypto analytics, security scanning, smart contract auditing, NLP tools, and more.
- **Endpoint**: `https://x402.alice-v0.workers.dev/v1/chat/completions`
- **Discovery**: `https://x402.alice-v0.workers.dev/.well-known/x402`
- **Price**: **$0.001-$0.05 USDC** per call (x402 protocol)
- **Capabilities**: `llm_proxy`, `crypto_analysis`, `security_scan`, `smart_contract_audit`, `nlp`, `data_analysis`
- **Status**: ✅ **Active & Verified**
- **Author**: VZero911
- **Repository**: [GitHub](https://github.com/VZero911)

#### 📊 How it works
1. Send a POST request to any endpoint (e.g., `/v1/chat/completions` for LLM, `/api/module/*` for tools).
2. x402 payment is handled automatically via Coinbase CDP facilitator.
3. Receive instant AI-powered results: LLM responses, crypto data, security reports, and more.

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x8E0014b38f3300f922100F2973b1bC749A626841`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

## 🚀 Add Your Service
Want to add your x402 agent service here?
1. Ensure your service is public and supports x402.
2. Submit a Pull Request with your service details in the format above.

---

*Last updated: 2026-10-13*
