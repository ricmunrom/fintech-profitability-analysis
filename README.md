# Fintech Profitability Analysis
*Business Analytics Case Study - Credit Portfolio Optimization & Collections Strategy*

## 📊 Executive Summary

This project analyzes the financial viability of a fintech startup offering two credit products over a 12-month projection period. The study reveals critical profitability challenges and evaluates the impact of implementing a targeted collections strategy to improve business performance.

### Key Results
- **Without Collections**: Net income deteriorates from -$236K (month 1) to -$2.2M (month 12)
- **With Collections**: 79% improvement in financial performance, reducing month 12 losses to -$466K
- **Optimized Strategy**: 35.2x ROI over 12 months with 7,310 accounts recovered

## 🎯 Business Problem

A fintech startup operates two credit products with concerning profitability metrics:

| Product | Loan Amount | Interest Rate | DQ Rate | Initial Customers | Monthly Growth |
|---------|-------------|---------------|---------|-------------------|----------------|
| Contigo A (High Risk) | $1,000 | 15% | 13.5% | 5,000 | 25% |
| Contigo B (Low Risk) | $2,000 | 10% | 8% | 10,000 | 10% |

**Challenge**: High delinquency rates and aggressive growth in the high-risk segment threaten business sustainability.

## 📈 Analysis Overview

### Part 1: Business State Analysis
- **Growth Impact**: 25% monthly growth in high-risk segment accelerates losses
- **Cost Scaling**: Linear operational costs ($30/account/month) from $450K to $2.6M
- **Revenue Imbalance**: Losses grow 5.5x vs revenue growth of 5.1x

### Part 2: Collections Strategy Design
- **Target Audience**: Contigo A delinquent customers
- **Methodology**: Phone-based recovery with contactability scoring
- **Success Metrics**: 75% payment probability if contacted

### Part 3: Integrated 12-Month Projection
- **Optimization**: Segmented approach targeting top 21.2% of DQ customers (scores >0.70)
- **Performance**: Consistent 94.4% success rate for high-score segment
- **Transformation**: Contigo A becomes most profitable product

## 🔧 Technical Implementation

### Tools & Technologies
- **Python**: Data analysis and financial modeling
- **Jupyter Notebooks**: Interactive analysis and visualization
- **Pandas**: Data manipulation and aggregation
- **Matplotlib/Seaborn**: Data visualization
- **Statistical Modeling**: Binomial probability models for campaign simulation

### Methodology
1. **Financial Projection Modeling**: 12-month cashflow projections with compound growth
2. **Stochastic Simulation**: Two-stage binomial model for collections outcomes
3. **ROI Analysis**: Cost-benefit analysis of collections strategies
4. **Segmentation Strategy**: Customer scoring and targeted interventions

## 📊 Key Findings

### Critical Success Factors
- **Segmented Collections**: 35.2x ROI vs 15x for unsegmented approach
- **Contactability Scoring**: Customers with scores >0.70 show 94.4% success rate
- **Product Transformation**: Collections converts Contigo A from liability to profit leader

### Financial Impact (12-Month Projection)

| Month | Without Collections | With Collections | Improvement |
|-------|-------------------|------------------|-------------|
| 1 | -$236,250 | -$86,440 | +63% |
| 6 | -$634,474 | -$174,904 | +72% |
| 12 | -$2,222,983 | -$466,283 | +79% |

## 📁 Repository Structure

```
fintech-profitability-analysis/
├── BA-1.ipynb                     # Business State Analysis
├── BA-2.ipynb                     # Collections Strategy Design  
├── BA-3.ipynb                     # Integrated 12-Month Projections
├── BA Hiring - Collections Challenge Excel (4) (3) (1) (3) (2) (3) (1) (1).xlsx
├── BA interview process_ Home test (Collections) (3) (3) (1) (2) (2) (4) (1) (1).docx
├── Business Analytics Challenge - Stori Fintech Startup.pdf
└── README.md
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis
1. Clone the repository
2. Install dependencies
3. Run notebooks in sequence:
   - Start with `BA-1.ipynb` (Business State Analysis)
   - Proceed to `BA-2.ipynb` (Collections Strategy)
   - Complete with `BA-3.ipynb` (Integrated Projections)

## 💡 Strategic Recommendations

### Immediate Actions (Months 1-3)
- Deploy segmented collections for high-score customers (>0.70)
- Reduce Contigo A growth rate from 25% to 15% monthly
- Implement basic automation tools

### Medium-term (Months 4-6)
- Expand collections to medium-score segments if ROI remains positive
- Implement multi-channel communication (SMS/email)
- Increase Contigo A interest rates to 18-20%

### Long-term (Months 7-12)
- Deploy AI-powered chatbots for initial contact
- Build automated risk management systems
- Develop intermediate risk products between A and B

## 📊 Business Impact

### Collections Performance
- **Total Accounts Recovered**: 7,310 over 12 months
- **Average Success Rate**: 94.3% for targeted segment
- **Total Collections Income**: $8,174,000
- **Net ROI**: 35.2x return on investment

### Product Transformation
- **Contigo A Evolution**: From -$306K to +$1.5M profitability (Month 12)
- **Market Position**: High-risk product becomes most profitable segment
- **Business Sustainability**: 79% improvement in overall financial performance

## 🎯 Business Analyst Skills Demonstrated

- **Financial Modeling**: Complex multi-product cashflow projections
- **Statistical Analysis**: Probability modeling and simulation
- **Strategic Planning**: Phased implementation roadmap
- **ROI Analysis**: Quantitative cost-benefit evaluation
- **Data-Driven Decision Making**: Evidence-based recommendations
- **Business Communication**: Executive-ready presentation of findings

## 📞 Contact

This analysis demonstrates proficiency in:
- Financial analysis and projections
- Risk assessment and mitigation strategies  
- Customer segmentation and targeting
- Campaign optimization and ROI analysis
- Strategic business recommendations

---
*This case study showcases end-to-end business analytics capabilities from problem identification through strategic solution implementation.*