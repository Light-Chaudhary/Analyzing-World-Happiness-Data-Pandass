# 🌍 World Happiness Report 2015 Analysis

This project uses data from the **World Happiness Report 2015** to explore global happiness trends, analyze contributing factors like GDP, support, and life expectancy, and highlight key insights.

## 🔗 Dataset

- Source: [World Happiness Report 2015](https://raw.githubusercontent.com/turdubars/World-Happiness/master/2015.csv)

## 📊 Features Used

- `Country`
- `Region`
- `Happiness Rank`
- `Happiness Score`
- `GDP` (Economy (GDP per Capita))
- `Support` (Family)
- `LifeExpectancy` (Health (Life Expectancy))

## 🧠 Operations Performed

- Selected only relevant columns
- Renamed columns to simpler, readable names
- Sorted top 10 happiest countries
- Identified countries with **high GDP but low happiness**
- Calculated **correlation** between Happiness Score, GDP, and Support
- Displayed bottom 10 least happy countries
- Exported both top and bottom lists to CSV

## 📈 Key Insights

- Countries like **Switzerland, Iceland, and Denmark** rank highest in happiness.
- Some nations have high GDP but still low happiness, suggesting money alone isn’t enough.
- **Support** and **GDP** both show strong correlation with happiness.

## 📂 Output Files

- `top10_happiest_country.csv`
- `least10_happy_countries.csv`

## 💻 Technologies

- Python
- Pandas
- CSV data processing

