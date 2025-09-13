# 🌍 Olympic Medal Trends by Continent

## 📖 Introduction
For my first project, I wanted to explore the history of the Olympic Games through the lens of medals.  

**Guiding Question:**  
> How have different continents contributed to Olympic medal counts over time?

This matters because the Olympics are more than just sports — they reflect historical, political, and cultural changes. Boycotts, new nations joining, and the growth of women’s participation all leave footprints in the medal counts.

---

## 📊 The Data
**Source:** Kaggle Olympic Games dataset (Summer & Winter Games)

**Key features include:**
- **Year** – The Olympic year  
- **City** – The host city  
- **Sport & Event** – Type of competition  
- **Athlete** – Participant’s name  
- **Country (NOC)** – The National Olympic Committee code for the country  
- **Medal** – Gold, Silver, or Bronze  

For this project, I focused on medal counts over time, mapping countries into continents to track broader regional performance.

---

## 🧹 Preprocessing the Data
To prepare the dataset, I:
- Combined Summer & Winter Games into one dataset  
- Mapped countries to continents using an NOC-to-continent dictionary  
- Deduplicated medals so team events only counted once  
- Aggregated by year and continent to sum medal counts across time  

These steps ensured consistency and fair comparisons.

---

## 📈 Data Visualization & Exploration
I created several visualizations to better understand medal trends:

### 1. Cumulative Medal Counts (Stacked Area Chart)
- Europe dominated the early Games  
- North America’s sharp growth coincided with the U.S. rise as a sporting power  
- Asia surged after the 1980s, especially with China’s emergence  

### 2. Normalized Trends (Proportion of Medals)
- Europe’s share declined as other continents gained prominence  
- Africa, while smaller in totals, consistently contributed in athletics and endurance sports  

### 3. Summer vs. Winter Olympics
- **Summer Games** → more diversity, many continents competing  
- **Winter Games** → concentrated in Europe and North America, shaped by climate and infrastructure  

---

## 🧠 Storytelling & Insights
Several patterns emerged from this analysis:

- Early Olympics were Europe-heavy due to location and limited participation  
- The Cold War era reshaped medal distributions, with surges from the USSR and Eastern Europe  
- Since the 1980s, Asia’s rise (especially China) shifted the global balance  
- Africa’s contributions highlight excellence in athletics despite lower total counts  

These shifts show how the Olympics reflect not only athletic achievements but also global power shifts and cultural change.

---

## ⚖️ Impact & Limitations
While these trends are fascinating, a few limitations must be acknowledged:

- **Population & Wealth** – Larger, wealthier countries field more athletes  
- **Event Distribution** – Some sports award many medals (e.g., swimming), skewing totals  
- **Gender & Access** – Women’s events expanded only recently, affecting comparisons  
- **Colonial & Geopolitical Bias** – Early Games excluded many regions, especially in Africa and Asia  

Recognizing these factors helps keep the analysis balanced.

---

## 📚 References
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)  
- [Seaborn Documentation](https://seaborn.pydata.org/)

---

## 💻 Code
The full code for this analysis and all visualizations can be found in the Jupyter Notebook:  
**`olympic_continent_trends.ipynb`**


