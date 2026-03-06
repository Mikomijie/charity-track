# CharityTrack 🛡️

**Tagline:** Bridging the trust gap in African Philanthropy through API-driven transparency.

## 👥 The Team
* **Michael Omijie** - System Architect & Integration Engineer 
* **Tochi Ajero** - Lead Frontend Developer

## 🚀 Project Overview
CharityTrack is a "Social Services" solution built for the **Build With Interswitch & Enyata Buildathon 2026**. 

In Nigeria and across Africa, many donors are hesitant to give to charities due to a lack of transparency. CharityTrack solves this by tracking every donation from the moment it is made until the moment it is spent on a verified service provider.

## 🛠️ The Problem
* **Trust Deficit:** Donors don't know if their money reaches the final destination.
* **Manual Reconciliation:** NGOs struggle with manual tracking of multiple small donations.
* **Fund Diversion:** Funds often don't reach the actual vendors (hospitals, suppliers, etc.).

## 💡 The Solution (Interswitch API Integration)
We leverage the Interswitch ecosystem to automate trust:
1. **Identity & Verification (KYC):** We use the **Interswitch BVN/CAC API** to verify every listed charity.
2. **Web Checkout (IPG):** Seamlessly collect donations via Cards, USSD, and Bank Transfers.
3. **Wallet Services (SVA):** Every project has a dedicated virtual wallet to hold funds securely.
4. **Disbursement (AutoPay):** Funds are paid directly to verified vendors/merchants, ensuring the money is used exactly for its intended purpose.

## 🏗️ Tech Stack
* **Architecture:** Vibe-Coded Backend (Node.js/Express) by Michael Omijie
* **Frontend:** Next.js & Tailwind CSS by Tochi Ajero
* **Database:** Supabase / MongoDB
* **APIs:** Interswitch Developer Gateway (Sandbox Mode)

## 🏁 Getting Started
1. Clone the repo: `git clone [https://github.com/Mikomijie/charity-track]`
2. Install dependencies: `npm install`
3. Set up `.env` with Interswitch `ClientID` and `Secret`.
4. Run the dev server: `npm run dev`

---
*Built with ❤️ for the Interswitch & Enyata Community Buildathon 2026.*
