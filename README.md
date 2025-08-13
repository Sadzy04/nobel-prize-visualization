# Nobel Prize Data Analysis

This project analyzes over a century of Nobel Prize awards, uncovering trends in categories, countries, gender representation, and award patterns. The analysis was completed as part of a DataCamp DataLab project.

---

## 📌 Project Overview
The Nobel Prize is one of the most prestigious international awards. This project explores the Nobel Prize dataset to identify historical trends, shifts in recognition, and representation across various demographics.

---

## 🛠 Tasks Completed

1. **Most Commonly Awarded Gender & Birth Country**  
   - Found the most frequently awarded gender and country of birth.  
   - Stored results in:
     ```python
     top_gender
     top_country
     ```

2. **Decade with Highest US-born Winner Ratio**  
   - Calculated the ratio of US-born winners to total winners for each decade.  
   - Identified the decade with the highest ratio.  
   - Stored result in:
     ```python
     max_decade_usa
     ```

3. **Decade & Category with Highest Proportion of Female Laureates**  
   - Determined which decade and Nobel Prize category combination had the highest proportion of female winners.  
   - Stored as a dictionary:
     ```python
     max_female_dict
     # Example: {1980: 'Literature'}
     ```

4. **First Woman to Receive a Nobel Prize**  
   - Identified the first female laureate and her award category.  
   - Stored results in:
     ```python
     first_woman_name
     first_woman_category
     ```

5. **Multiple Nobel Prize Winners**  
   - Found individuals or organizations who have won more than one Nobel Prize.  
   - Stored as a list:
     ```python
     repeat_list
     ```


---

## 📊 Technologies Used
- **Python**: Pandas, Matplotlib, Seaborn
- **Jupyter Notebook**
- DataCamp DataLab environment

---

## 📂 Dataset
Dataset provided by DataCamp's Nobel Prize project (public domain or educational use).  
Contains details such as:
- Year of award
- Category (Physics, Chemistry, Medicine, Literature, Peace, Economics)
- Country of birth
- Gender
- prize	motivation
- -prize_share
- laureate_id
- laureate_type
- full_name
- birth_date
- birth_city	
- organization_name	
- organization_city
- organization_country
- death_date
- death_city
- death_country


---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/nobel-prize-data-analysis.git
   cd nobel-prize-data-analysis
