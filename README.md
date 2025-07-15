# Iranian Students Population Analysis

A comprehensive data analysis project examining the demographic trends of Iranian students across different educational levels from 1968 to 2016 (Persian calendar: 1347-1395).

## 📊 Project Overview

This project analyzes the population dynamics of Iranian students over nearly five decades, providing insights into:
- Gender distribution trends across different educational levels
- Changes in student enrollment patterns over time
- Impact of educational system reforms on student demographics
- Comparative analysis of male and female student populations

## 🗂️ Dataset

The analysis is based on data from `Iranian_students_population.xlsx` which contains:
- **Time Period**: 1968-2016 (Persian calendar: 1347-1395)
- **Educational Levels**: 
  - Preschool
  - Primary school
  - Junior high school (Middle school)
  - High school (Secondary school)
- **Demographics**: Gender-segregated data for each educational level

## 🔍 Key Findings

### Gender Distribution Trends
- **Historical Male Dominance**: In 1971 (1350), male students significantly outnumbered female students
- **Gradual Shift**: Starting from 1973 (1352), female student enrollment began increasing steadily
- **Current Status**: While the gap has narrowed considerably, male students still slightly outnumber female students overall

### Educational System Reform Impact
- **System Change**: The analysis reveals the clear impact of Iran's educational system reform in 2012 (1391-1392)
- **5-3-4 to 6-3-3 Transition**: The change from a 5-3-4 system to a 6-3-3 system caused:
  - Significant drop in junior high school enrollment
  - Increase in primary school enrollment
  - Students who would have moved from 5th grade to junior high remained in 6th grade of primary school

## 📈 Visualizations

The project includes various visualizations:
- Bar charts showing total male and female student populations over time
- Line graphs displaying gender ratios across different educational levels
- Trend analysis of each educational level's share of total student population
- Comparative analysis of educational level distributions

## 🛠️ Technical Stack

- **Python 3.x**
- **Libraries Used**:
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `matplotlib` - Data visualization
  - `arabic_reshaper` - Persian text reshaping
  - `bidi` - Bidirectional text support

## 📁 File Structure

```
├── Iranian_students_population.py    # Main analysis script
├── Iranian_students_population.xlsx  # Dataset
└── README.md                        # Project documentation
```

## 🚀 Getting Started

### Prerequisites

Install required packages:
```bash
pip install pandas numpy matplotlib arabic-reshaper python-bidi
```

### Running the Analysis

1. Clone the repository:
```bash
git clone https://github.com/yourusername/iranian-students-analysis.git
cd iranian-students-analysis
```

2. Ensure the Excel file `Iranian_students_population.xlsx` is in the same directory

3. Run the analysis:
```bash
python Iranian_students_population.py
```

## 📊 Generated Outputs

The script generates several visualizations:
- Total male students by academic year
- Total female students by academic year
- Male-to-female ratio trends
- Gender ratios for each educational level
- Educational level distribution over time

## 🔧 Code Features

- **Persian Text Support**: Proper handling and display of Persian text in visualizations
- **Data Transformation**: Comprehensive data cleaning and restructuring
- **Statistical Analysis**: Calculation of ratios and proportions across different dimensions
- **Custom Plotting Function**: Reusable visualization function for consistent chart formatting

## 📚 Educational Context

This analysis provides valuable insights into:
- **Social Changes**: The gradual increase in female education participation
- **Policy Impact**: How educational reforms affect student distribution
- **Demographic Trends**: Long-term patterns in Iranian education system
- **Gender Equality**: Progress toward gender parity in education

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Submit bug reports
- Suggest new features
- Improve documentation
- Add additional analysis

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

For questions or suggestions, please open an issue or contact [your-email@example.com]

---

**Note**: This analysis is based on historical data and provides insights into past trends. For current statistics, please refer to the latest official sources from Iran's Ministry of Education.
