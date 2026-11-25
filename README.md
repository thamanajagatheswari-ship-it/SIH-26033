## Smart India Hackathon Workshop
## Date:23/11/2026
## Reference Number:26018758
## Name:Thamana G

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution

1. Detailed Explanation of the Proposed Solution
We propose a unified digital marketplace that connects farmers and Farmer Producer Organizations (FPOs) directly with consumers and bulk buyers, removing the need for multiple intermediaries. The platform is accessible through a multilingual mobile application, a web portal, and voice/SMS support for farmers with limited digital literacy.

The solution consists of four integrated components:
(a) Direct Trading Module: Farmers and FPOs list their produce with quantity, quality grade, and expected price. Consumers place retail orders, while bulk buyers such as hotels, retailers, and institutions place bulk orders or enter forward contracts.
(b) Logistics Support Module: Produce is aggregated at village-level collection points, graded, weighed, and tagged with QR codes. Pooled transport and last-mile delivery are arranged through partner logistics providers with live GPS tracking.
(c) AI Engine: The platform uses machine learning for demand forecasting and fair-price recommendation, and optimization algorithms for route planning and load pooling.
(d) Secure Payment Module: Payments are held in escrow and released directly to the farmer's bank account or UPI after the buyer accepts the delivery.

2. How It Addresses the Problem
The traditional supply chain passes produce through several intermediaries, each adding a margin. This lowers the price received by the farmer and raises the price paid by the consumer. Our solution addresses this in the following ways:
- Direct farmer-to-buyer trade replaces multiple intermediaries, so the margin earlier captured by them is shared between the farmer and the consumer.
- AI-based demand forecasting helps farmers plan sales and reduces wastage and distress selling.
- Route optimization and load pooling reduce transport cost per unit of produce.
- Transparent pricing, escrow payments, and a rating system build trust between farmers and buyers.
- Aggregation through FPOs enables small and marginal farmers to supply bulk orders.

3. Innovation and Uniqueness of the Solution
- Inclusive access through regional languages, voice, and SMS interfaces designed for rural users.
- FPO-based aggregation that enables small farmers to participate in bulk contracts.
- An AI-driven fair-price band that shows the farmer's share of the final consumer price.
- Pooled logistics that combines multiple small orders on a common route to reduce cost.
- QR-based quality grading and traceability from farm to consumer.
- A feedback loop in which ratings and delivery data continuously improve forecasting and pricing models.

## Technical Approach

1. Technologies to be Used
- Frontend: React Native (Android and iOS mobile application), React.js (web portal), IVR/SMS gateway for voice and text access.
- Backend: Python (FastAPI) or Node.js, with RESTful APIs and an API gateway.
- Database: PostgreSQL with PostGIS for geospatial data; Redis for caching.
- Artificial Intelligence and Machine Learning:
  - Demand forecasting using time-series models (Prophet, XGBoost, or LSTM) trained on historical orders, seasonality, weather, and mandi price data.
  - Price recommendation using regression-based models.
  - Route optimization and load pooling using Google OR-Tools (Vehicle Routing Problem solver).
- Data Sources: Agmarknet (mandi prices), eNAM, and India Meteorological Department (weather data).
- Payments: UPI integration and escrow-based settlement.
- Maps and Tracking: OpenStreetMap or Google Maps API with GPS-based live tracking.
- Cloud and Deployment: Docker containers on AWS, Azure, or Google Cloud.
- Hardware (optional): Digital weighing scales and QR label printers at village collection points.

2. Methodology and Process for Implementation
Step 1: Farmers and FPOs register on the platform with KYC verification and list their produce.
Step 2: Consumers place retail orders at listed prices; bulk buyers place bids or enter forward contracts.
Step 3: The AI engine generates demand forecasts, recommends fair prices, and plans optimized delivery routes.
Step 4: The buyer makes the payment, which is held in escrow.
Step 5: Produce is aggregated at the village collection point, where it is graded, weighed, and QR-tagged.
Step 6: Pooled transport delivers the produce to buyers with live tracking.
Step 7: On delivery acceptance, payment is released to the farmer. Disputes are handled through a refund and resolution process.
Step 8: Ratings, feedback, and transaction data are fed back to improve the AI models.

## Flow Chart:

<img width="675" height="836" alt="Screenshot 2026-11-25 102002" src="https://github.com/user-attachments/assets/0d8af5d3-cb32-4167-af3c-3f912bf7f90f" />


## Feasibility and Viability

1. Analysis of the Feasibility of the Idea
- Technical Feasibility: All proposed components, including mobile applications, forecasting models, route optimization solvers, and UPI payments, are based on mature, widely available technologies and open-source tools.
- Operational Feasibility: Existing structures such as FPOs, cooperatives, and Common Service Centres can serve as village-level aggregation and onboarding points.
- Economic Viability: The platform can generate revenue through a small commission on transactions, logistics service margins, and premium analytics services for bulk buyers. The commission is expected to be significantly lower than the margins taken by intermediaries.
- Policy Alignment: The solution is consistent with government initiatives such as Digital India, eNAM, the FPO promotion scheme, and the Open Network for Digital Commerce (ONDC), which supports integration and adoption.

2. Potential Challenges and Risks
- Limited digital literacy and internet connectivity in rural areas.
- The initial difficulty of attracting enough farmers and buyers simultaneously.
- Spoilage and quality disputes in perishable commodities.
- High last-mile logistics costs in remote locations.
- Resistance from existing traders and intermediaries.
- Risks of payment fraud and price manipulation.

3. Strategies for Overcoming These Challenges
- Provide voice, IVR, and regional-language interfaces, and appoint local agents to assist with onboarding and training.
- Begin with a pilot in a single district or cluster with a limited number of crops, then scale progressively.
- Use grading at collection points, QR-based traceability, and photo-based proof to reduce spoilage disputes.
- Use pooled transport and partnerships with existing logistics providers to lower delivery costs.
- Engage existing traders as aggregation and transport partners instead of excluding them.
- Implement KYC verification, escrow payments, and AI-based anomaly detection to prevent fraud and price manipulation.

## Impact and Benefits

1. Potential Impact on the Target Audience
- Farmers and FPOs: Higher realized price per unit of produce, faster and transparent payments, and better visibility of market demand for planning.
- Consumers: Access to fresher produce at lower prices, with traceability of origin and quality.
- Bulk Buyers: Reliable supply, contract-based pricing, and quality assurance.
- Government and Policymakers: Transparent, real-time price and supply data to support planning and policy decisions, and reduced post-harvest losses.

2. Benefits of the Solution
- Social: Improved rural livelihoods, inclusion of small and marginal farmers, and greater participation of women-led FPOs and self-help groups in the market.
- Economic: A reduced gap between farm-gate and retail prices, lower transaction costs, reduced wastage, and a more efficient supply chain.
- Environmental: Reduced food miles through optimized routing, lower spoilage and food waste, and a consequent reduction in associated emissions.

 ## Research and References

1. Smart India Hackathon, Problem Statement SIH 26033: Multiple intermediaries reduce farmers' earnings and increase consumer prices (Ministry of Consumer Affairs, Food & Public Distribution).
2. Agmarknet, Government of India: https://agmarknet.gov.in
3. National Agriculture Market (eNAM): https://enam.gov.in
4. Ministry of Agriculture and Farmers Welfare, Scheme for Formation and Promotion of 10,000 Farmer Producer Organizations (FPOs).
5. Open Network for Digital Commerce (ONDC): https://ondc.org
6. Google OR-Tools, Vehicle Routing Problem documentation: https://developers.google.com/optimization/routing
7. [Add one or two studies on the farmer's share of the consumer price, for example from NABARD, ICRIER, or the Economic Survey of India, to support the impact claims.]

