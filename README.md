# Hotel Booking Analysis & Revenue Optimization

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)]()

> **Business Analyst Intern Assignment for TravClan**  
> Comprehensive analysis of 30,000 hotel booking transactions identifying revenue optimization opportunities worth INR 19.8 crore annually

---

## 📊 Project Overview

This project analyzes hotel booking data spanning **January 2024 to December 2025**, focusing on cancellation patterns, revenue distribution, and strategic recommendations to optimize booking performance and reduce revenue loss.

### Key Metrics Analyzed
- **Total Bookings:** 30,000
- **Total Revenue:** INR 89.22 crore
- **Cancellation Rate:** 19.26%
- **Data Period:** 24 months
- **Properties Analyzed:** 4 hotels across 10 cities

---

## 🎯 Key Findings

### 1. Channel-Based Cancellation Disparity
- **Travel Agent:** 26.29% cancellation rate (highest)
- **Mobile App:** 22.42% cancellation rate
- **Web:** 15.33% cancellation rate (lowest)
- **Impact:** INR 10.27 crore potential annual recovery

### 2. Weekend vs Weekday Booking Behavior
- **Weekend Check-ins:** 4.46% cancellation rate
- **Weekday Check-ins:** 27.20% cancellation rate
- **Difference:** 6.1x higher cancellations on weekdays
- **Impact:** INR 15.75 crore in lost booking value

### 3. Room Type Performance
- **Standard Rooms:** 22.12% cancellation rate (63.4% of all cancellations)
- **Premium Rooms (Deluxe/Suite):** ~15.7% cancellation rate
- **Impact:** 41% higher cancellation in standard rooms

---

## 💡 Strategic Recommendations

| Recommendation | Target Impact | Annual Revenue Recovery |
|----------------|---------------|-------------------------|
| **Channel-Specific Strategy** | Reduce Travel Agent cancellations from 26.29% to 18% | INR 8.98 crore |
| **Weekday Optimization** | Reduce weekday cancellations from 27.20% to 15% | INR 8.30 crore |
| **Room Type Strategy** | Reduce standard cancellations from 22.12% to 17% | INR 2.52 crore |
| **Total Potential** | Overall cancellation rate: 19.26% → 12-13% | **INR 19.80 crore** |

---

## 🛠️ Technologies & Tools

### Data Analysis
- **Python 3.11+** - Core analysis and statistical computations
  - `pandas` - Data manipulation and analysis
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical graphics
  - `scipy` - Statistical methods
  
### Data Processing
- **Microsoft Excel** - Data cleaning and validation
- **SQL** - Complex multi-dimensional queries

### Visualization & Reporting
- **Power BI** - Interactive dashboards
- **LaTeX** - Professional report generation

---

## 📁 Project Structure

```
Travclan/
│
├── data/
│   ├── raw/                      # Original dataset
│   └── processed/                # Cleaned and transformed data
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb    # Data preprocessing
│   ├── 02_eda.ipynb              # Exploratory data analysis
│   ├── 03_cancellation_analysis.ipynb
│   └── 04_revenue_analysis.ipynb
│
├── src/
│   ├── data_processing.py        # Data cleaning functions
│   ├── analysis.py               # Statistical analysis
│   └── visualization.py          # Custom plotting functions
│
├── dashboards/
│   └── hotel_booking_dashboard.pbix  # Power BI dashboard
│
├── reports/
│   ├── TravClan_Report.pdf       # Final assignment report
│   └── presentation.pptx         # Executive summary
│
├── sql/
│   └── queries.sql               # SQL analysis queries
│
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.11 or higher
- Microsoft Excel (optional)
- Power BI Desktop (optional, for dashboards)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/vijaysingh091/Travclan.git
cd Travclan
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

### Running the Analysis

```bash
# Run data cleaning
python src/data_processing.py

# Run main analysis
python src/analysis.py

# Generate visualizations
python src/visualization.py
```

### Jupyter Notebooks

```bash
jupyter notebook
# Navigate to notebooks/ directory and run in sequence
```

---

## 📈 Analysis Highlights

### Revenue Distribution by Channel
| Channel | Revenue (INR Crore) | Share | Avg Booking Value |
|---------|---------------------|-------|-------------------|
| Web | 44.95 | 50.4% | INR 29,962 |
| Mobile App | 35.41 | 39.7% | INR 29,490 |
| Travel Agent | 8.86 | 9.9% | INR 29,644 |

### Top Revenue Cities
1. **Chicago** - INR 9.15 crore
2. **Los Angeles** - INR 9.12 crore
3. **San Francisco** - INR 9.05 crore
4. **Las Vegas** - INR 9.00 crore
5. **Orlando** - INR 8.96 crore

### Hotel Star Rating Performance
- **5-Star Hotels:** 19.11% cancellation rate
- **4-Star Hotels:** 18.14% cancellation rate (best performance)
- **3-Star Hotels:** 20.42% cancellation rate
- **2-Star Hotels:** 19.97% cancellation rate

---

## 📊 Visualizations

The project includes comprehensive visualizations:
- Cancellation rate comparisons across channels
- Weekend vs weekday booking patterns
- Room type performance analysis
- Revenue distribution charts
- Monthly trend analysis
- Geographic revenue heatmaps

*See the `dashboards/` folder for interactive Power BI reports*

---

## 🎓 Methodology

### Data Quality Assessment
- **Total Records:** 30,000 (100% complete for revenue/cancellation)
- **Missing Data:** 18.23% missing check-in/check-out dates
- **Validation:** No duplicates, consistent monetary values
- **Profit Margin:** Consistent 31% across all segments

### Statistical Methods
- Descriptive statistics (mean, median, standard deviation)
- Group-by aggregations across multiple dimensions
- Comparative analysis and cross-tabulation
- Time series trend analysis
- Quantile-based customer segmentation

### Root Cause Analysis Framework
Applied systematic root cause analysis for:
- Channel-based cancellation patterns
- Weekday vs weekend booking behavior
- Room type cancellation drivers

---

## 💼 Business Impact

### Implementation Roadmap

| Phase | Timeline | Action |
|-------|----------|--------|
| Phase 1 | Weeks 1-2 | Travel Agent deposit policy |
| Phase 2 | Weeks 3-6 | Mobile App UX optimization |
| Phase 3 | Weeks 7-10 | Weekday incentive programs |
| Phase 4 | Weeks 11-14 | Room type policy rollout |
| Phase 5 | Week 15+ | Monitoring and optimization |

### Success Metrics
- Cancellation rate by channel (Target: <18% all channels)
- Weekend vs weekday booking mix
- Room type distribution and upgrade adoption
- Revenue per booking
- Customer retention and repeat booking rate
- Booking credit redemption rate

---

## 📝 Key Recommendations Summary

### 1. Channel-Specific Cancellation Strategy
- Implement 20% non-refundable deposit for Travel Agent bookings
- Optimize Mobile App booking flow and user experience
- Replicate Web channel success factors

### 2. Weekday Booking Optimization
- Allow free date changes up to 7 days before check-in
- Introduce "Weekday Warrior" loyalty program
- Offer corporate rates with deposit requirements

### 3. Room Type Strategy
- Implement differential deposit policies by room type
- Create upgrade incentive programs
- Adjust room inventory mix (reduce standard, increase deluxe)

---

## 📄 Report

The complete analysis report is available in `reports/TravClan_Report.pdf`, which includes:
- Executive Summary
- Detailed Key Observations
- Root Cause Analysis
- Business Recommendations
- Additional Analysis (Revenue, Cities, Star Ratings)
- Implementation Roadmap
- Success Metrics

---

## 🤝 Contributing

While this is an assignment project, feedback and suggestions are welcome! Feel free to:
1. Open an issue for bugs or suggestions
2. Fork the repository for your own analysis
3. Submit pull requests for improvements

---

## 👤 Author

**Vijay Bhushan Singh**
- Email: vijay3420blw@gmail.com
- GitHub: [@vijaysingh091](https://github.com/vijaysingh091)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/vijaysingh091)

---


## 🙏 Acknowledgments

- **TravClan** for the assignment opportunity and dataset
- Hospitality industry research papers for cancellation pattern insights
- Open-source community for excellent data analysis tools

---

## 📞 Contact

For questions, collaboration, or opportunities:
- **Email:** vijay3420blw@gmail.com
- **Project Link:** [https://github.com/vijaysingh091/Travclan](https://github.com/vijaysingh091/Travclan)

---
