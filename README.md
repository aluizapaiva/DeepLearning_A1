# Bond Bank Customer Targeting System

## Project Overview
This is my 1st ANN project focused on customer targeting system for Bond Bank's telemarketing team to predict which customers are most likely to accept term deposit offers. The solution transforms random calling strategies into precision targeting, improving conversion rates from 12% to 38%.

## Business Context
**Problem**: Current telemarketing approach is largely random, resulting in:
- Only 12% success rate on calls
- 88% of efforts directed toward uninterested customers  
- Customer irritation from unwanted calls
- Wasted resources on low-probability leads

**Solution**: An intelligent targeting system that analyzes customer data to predict interest levels with 84% accuracy, enabling the sales team to focus on high-probability prospects.

## Technical Approach

### Model Architecture
- **Primary Model**: Feedforward Artificial Neural Network (ANN)
- **Task Type**: Binary classification (yes/no to term deposit offer)
- **Input**: Customer demographic and interaction history data
- **Output**: Probability score for term deposit acceptance

### Dataset
- **Source**: Bond Bank telemarketing campaign data (Term_Deposit_Campaign.csv)
- **Size**: 45,000+ customer interactions
- **Features**: Demographics, contact history, economic indicators, previous campaigns
- **Target Variable**: Term deposit subscription (yes/no)

### Performance Results
- **Model Accuracy**: 84%
- **Targeted Campaign Success**: 38% (vs 12% random)
- **Efficiency Improvement**: 3x more effective than current approach
- **Customer Satisfaction**: Reduced unwanted calls by 68%

## Repository Structure
```
bond-bank-targeting/
├── bank_targeting_analysis.ipynb    # Main technical notebook
├── management_report.pdf            # Executive summary for telemarketing team
├── data/                           # Dataset files
│   ├── Term_Deposit_Campaign.csv
│   └── Data_Dictionary.xlsx
├── models/                         # Saved model files
├── results/                        # Performance metrics and visualizations
└── README.md                       # This file
```

## Key Business Insights
- **Ideal Customer Profile**: Students and retirees show 2x higher conversion rates
- **Optimal Timing**: March and September-December offer highest success rates
- **Age Demographics**: Focus on 18-24 and 65+ age groups for best results
- **Contact Strategy**: Success declines after 3-4 attempts; first calls most effective

## Strategic Impact
- **Efficiency**: Sales team focuses on high-probability customers
- **Customer Experience**: Minimizes unsolicited calls, protecting brand reputation
- **Competitive Advantage**: Precision targeting vs competitors' random approaches
- **Scalability**: Framework adaptable for future product campaigns

## Technologies Used
- **Python**: Primary programming language
- **ANN Architecture**: Feedforward neural networks for classification
- **Data Analysis**: Pandas, NumPy for data preprocessing
- **Visualization**: Matplotlib, Seaborn for business insights
- **Google Colab**: Development and training environment

## Model Performance
| Metric | Current Random Approach | AI Targeting System |
|--------|------------------------|-------------------|
| Success Rate | 12% | 38% |
| Efficiency | High volume, low success | 3x more effective |
| Customer Experience | High complaint risk | Reduced unwanted calls |

## Installation & Usage
1. Clone this repository
2. Install required dependencies: `pip install tensorflow pandas numpy matplotlib seaborn scikit-learn`
3. Open `bank_targeting_analysis.ipynb` in Jupyter or Google Colab
4. Follow the notebook cells for model training and evaluation

## Reports Included
- **Management Report**: Business-focused summary for telemarketing team leadership
- **Technical Report**: Detailed Jupyter notebook with complete methodology and code

## Academic Context
**Course**: DTSC301 - Deep Learning Through Neural Networks  
**Institution**: Bond University  
**Assessment**: Written Report 1 (30% weighting)  
**Focus**: Real-world application of ANNs in banking and marketing

## Implementation Strategy
1. **Pilot Phase**: Test with small customer segment
2. **CRM Integration**: Connect model output with existing call systems
3. **Team Training**: Minimal training required for telemarketing staff
4. **Performance Monitoring**: Track conversion rates and customer feedback

## Risk Management
- Tested with historical data for validation
- Backup calling methods available during transition
- Continuous monitoring of model performance
- Customer satisfaction tracking

## Contact
Ana Luiza Lerch Paiva  
Data Analytics Student, Bond University  
GitHub: @aluizapaiva

---
*This project demonstrates the application of neural networks to improve business efficiency and customer experience in banking telemarketing operations.*
