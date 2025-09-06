# CCROWN - Churn, CLV, and Revenue Optimization with Neural-Networks Using an End-to-End Multi-Task Hybrid Ensemble Framework with Attention for iOS and macOS Deployment

## License
This project is **dual-licensed**:
- 🧪 Free for non-commercial academic and research use.
- 💼 Commercial use requires written permission.
See [LICENSE.txt](./LICENSE.txt) for full terms.  
Contact: harminder_24a03res132@iitp.ac.in

# Abstract
Despite extensive research on customer churn prediction (CP) and customer lifetime value (CLV)
estimation, current approaches suffer from fragmented predictions, lack temporal awareness, and
lack explainability, which limits their strategic utility. To address these challenges, we introduce
CCROWN, a novel multi-task hybrid neural ensemble with dynamic attention weighting that 
simultaneously predicts churn, CLV, and survival risk. CCROWN is not just an improvement, but a
necessary evolution in customer analytics.

CCROWN translates predictions into actionable strategy by automatically segmenting cus
tomers. It identifies a critical cohort of ‘At-Risk Gems’, representing fraction of customers
that drives majority of preventable revenue loss, thus allowing for highly targeted retention efforts. 
Our framework demonstrates a significant improvement in predictive accuracy over isolated models 
while reducing computational costs through hardware-aware optimization.

The framework introduces: 
(1) Three parallel neural backbones (MLP, ResNet, DeepNet) with dynamic attention weighting; 
(2) A Cox Proportional Hazards survival head for temporal risk modeling; 
(3) Automated segmentation into actionable customer cohorts to prioritize high-value retention
 strategies, potentially reducing acquisition costs and increasing retention ROI. The system achieves
 state-of-the-art performance across 6 industry datasets (telecom, banking, e-commerce) with full
 reproducibility via our open-source Python implementation.
