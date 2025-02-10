# FGP-01: Stay Liquid

## Contact Information
- **Email**: misha@stayliquid.co  
- **Telegram**: @anotherfuturist  

---

## Summary  
Stay Liquid proposes an integration with the **Frankencoin Savings module** to enhance liquidity and introduce a Swiss Franc (ZCHF)-backed yield option for businesses.  

### **Project Overview**  
Stay Liquid is a **business savings account** that allows Web2 companies to **deploy surplus cash into DeFi stablecoin yield opportunities** while maintaining liquidity. Currently, Stay Liquid operates on **Arbitrum One**, utilizing USD-backed stablecoins for yield generation across **DEXes and lending protocols**.  

This proposal aims to **expand Stay Liquid’s stablecoin portfolio** by integrating **ZCHF (Frankencoin)** into its savings strategies, enabling businesses to **diversify their exposure beyond USD-backed assets**.  

### **Why This Matters**  
- **Businesses Get Access to Non-USD Stablecoins** – Reducing reliance on US-dollar-based stablecoins enhances financial resilience.  
- **Frankencoin Benefits from Increased TVL** – More liquidity flows into the **Frankencoin Savings module**.  
- **More Exposure for ZCHF** – Web2 businesses get introduced to **Frankencoin as their first DeFi stablecoin**, expanding adoption.  

---

## Motivation  
Frankencoin is a **decentralized, collateral-backed stablecoin pegged to the Swiss Franc**, offering an **oracle-free and highly decentralized alternative** to traditional stablecoins. However, mass adoption of **ZCHF as a savings vehicle** requires deeper integration into the DeFi ecosystem.  

Stay Liquid’s **business-friendly approach** enables Web2 companies to **earn yield in stablecoins without deep DeFi knowledge**, providing an **accessible and regulated way to increase ZCHF adoption**.  

---

## Benefit to the Frankencoin Ecosystem  
### **Key Contributions**  
1. **Increase in Frankencoin Savings TVL** – More liquidity locked in **ZCHF savings pools**.  
2. **Access to Web2 Business Capital** – Introduces **traditional finance users** to the Frankencoin ecosystem.  
3. **Stronger Market Position for ZCHF** – Expands the use case beyond individual DeFi users.  

By onboarding Stay Liquid’s user base, **Frankencoin will gain adoption among businesses** that typically only interact with **fiat-based finance**.  

---

## Specification  

### **Project Overview**  
- **Category**: DeFi Integration  
- **Team Members**:  

  #### **Misha Kushka** – **Stay Liquid Co-founder & CTO, Web3 Developer**  
  - **GitHub**: [@kushkamisha](https://github.com/kushkamisha)  
  - **LinkedIn**: [Misha Kushka](https://www.linkedin.com/in/mkushka/)  
  - **Experience**:  
    - Web3 developer since **2016**, specializing in **DeFi and smart contract development**.  
    - **Open-source contributor** with NPM packages for **TRON blockchain** ([tron-format-address](https://www.npmjs.com/package/tron-format-address)).  
    - **Core contributor** to **Pairwyse DSL**, a domain-specific language for smart contract logic. [GitHub link](https://github.com/akiva-capital-holdings/pairwyse-dsl).
    - **Lead developer** of DAOsign, a decentralized document-signing protocol. [GitHub link](https://github.com/DAOsign).
    - Extensive experience in **DeFi integrations and yield optimization strategies**.  

  #### **Oleg Vantkovskyi** – **Senior Software Engineer, DevOps & Web3 Specialist**  
  - **GitHub**: [@oLewar](https://github.com/oLewar)  
  - **LinkedIn**: [Oleg Vantkovskyi](https://www.linkedin.com/in/vantkovsky/)  
  - **Experience**:  
    - **20+ years** in software engineering, **leading teams** and developing **highly scalable applications**.
    - **Built DeFi integrations** for personal and enterprise-level projects, ensuring security and efficiency.
    - Strong background in **DevOps, and cloud infrastructure**: Terraform, Helm, AWS, Hezner, and other tools.

### **Project Description**  
Stay Liquid will **integrate Frankencoin Savings into its yield strategies**, allowing businesses to **diversify stablecoin holdings with ZCHF**.  

Currently, Stay Liquid enables **fiat-to-stablecoin conversion in the background** before funds are deployed into DeFi protocols. Post-integration, Stay Liquid will offer **ZCHF as a yield-earning option**, improving diversification and increasing ZCHF adoption.  

### **Technical Approach**  
- **Backend**: TypeScript, NestJS  
- **Smart Contracts**: Solidity (Integration with Frankencoin's **Savings module**)  

Stay Liquid will use **Frankencoin’s existing Ethereum smart contracts** but adapt the architecture for **Arbitrum One**, where its current operations are based.  

### **Expected Outcome**  
- **Seamless integration** with [Frankencoin’s Savings module](https://github.com/Frankencoin-ZCHF/FrankenCoin/blob/main/contracts/Savings.sol).  
- **Increased TVL in ZCHF pools**, attracting more liquidity.  
- **Business clients onboarded into DeFi using ZCHF as a stable yield option**.  

---

## Milestones & Deliverables  

| Milestone  | Deliverable  | Estimated Completion  |
|------------|-------------|----------------------|
| **1** | Initial Prototype | **2025-03-03** |
| **2** | Beta Version | **2025-04-01** |
| **3** | Final Release | **2025-05-01** (depends on Frankencoin Savings module deployment to Arbitrum One) |

---

## Funding Request  
- **Total Grant Amount Requested**: 10,000 CHF  
- **Funding Breakdown**:  
  - Development & Integration
  - Smart Contract Audits: integration with our Fee Collector smart contract
  - Infrastructure & Deployment Costs

---

## Risks & Challenges  
### **Key Challenge**  
Frankencoin’s **Savings module is currently only on Ethereum mainnet**, while Stay Liquid operates on **Arbitrum One**.  

### **Mitigation Plan**  
1. **Short-Term** – Utilize existing Ethereum smart contracts via function signatures.  
2. **Long-Term** – Migrate as soon as **Frankencoin’s Savings module is deployed to Arbitrum One**.  

Since **Frankencoin’s team has confirmed** upcoming Arbitrum One support, this integration **is not blocked** but will evolve as infrastructure improves.  

---

## Community & Engagement  
- **How will you involve the Frankencoin community?**  
  - Announce integration on **Stay Liquid’s website & social media**.  
  - Engage with **Frankencoin’s community on Telegram and other platforms**.  
  - Open to being **listed as an official Frankencoin partner**.  

- **Will your project be open-source?**  
  - **No**, but integration details will be made transparent.  

- **How do you plan to maintain the project post-grant?**  
  - **Yes**, Stay Liquid will continue expanding to **more chains & DeFi protocols**, maintaining ZCHF as a core diversification option.  

---

## Additional Information  
- **[Stay Liquid Website](https://www.stayliquid.co/)**  
- **[Frankencoin Savings Module Smart Contracts](https://github.com/Frankencoin-ZCHF/FrankenCoin/tree/main)**  

---

## Submission Checklist  
✅ The proposal follows the **FGP format**.  
✅ The proposal is submitted as a **PR to the Frankencoin Grants repository**.  
✅ The project aligns with **Frankencoin ecosystem goals**.  

---

## Grant Decision & Results  
(To be completed by **Frankencoin Association Members**)  

### **Date of Decision**:  
[YYYY-MM-DD]  

### **Status**:  
[Granted/Denied/Postponed]  

### **Amount Granted**:  
[Amount in CHF]  

### **Payment Schedule**:  
[Describe the payment plan]  

### **Comments**:  
[Additional remarks]  

---
**Disclaimer**: The **Frankencoin Association** reserves the right to review, request modifications, or reject any proposal at its discretion.