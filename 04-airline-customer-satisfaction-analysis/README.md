# ✈️ Airline Customer Satisfaction Analysis

## 📌 Project Overview

This project analyzes airline customer satisfaction data using **Microsoft Excel** with a strong focus on **Business Class customer experience, service prioritization, flight-distance behavior, demographic segmentation, and operational experience metrics**.

The objective was not only to calculate satisfaction scores, but also to identify:

- Which service areas create the strongest customer experience
- Which service areas require immediate improvement
- How flight distance changes across travel classes
- Whether age and gender create meaningful differences in satisfaction
- Whether operational delays explain customer perception
- Which findings should be translated into actionable business decisions

The project follows a **business-first analytics approach**:

**Business Question → Excel Analysis → Insight → Business Implication → Recommended Action**

---

## 📊 Dataset

The dataset contains **103,904 passenger records** and includes variables such as:

- Gender
- Age
- Type of Travel
- Class
- Flight Distance
- Inflight Wi-Fi Service
- Departure / Arrival Time Convenience
- Online Booking Experience
- Gate Location
- Food & Drink
- Online Boarding
- Seat Comfort
- Inflight Entertainment
- On-board Service
- Leg Room Service
- Baggage Handling
- Check-in Service
- Inflight Service
- Cleanliness
- Departure Delay
- Arrival Delay
- Satisfaction
- NPS

A separate **Business Class sample of 7,111 passengers** was also analyzed in detail.

---

# 🎯 Business Questions

The analysis focused on the following questions:

1. Which service attributes generate the highest and lowest satisfaction among Business Class passengers?
2. Which service attributes should be prioritized based on both **importance and satisfaction**?
3. Does flight distance differ across Business, Economy and Economy Plus passengers?
4. How do selected service scores change across age and gender segments?
5. Which customer segments report the lowest satisfaction scores?
6. How does **Departure / Arrival Time Convenience** relate to flight distance and operational delays?

---

# 🔍 Analysis & Key Findings

## 1. Business Class Service Performance

Business Class customers show strong satisfaction with operational service areas.

### Strongest Service Areas

| Service Attribute | Satisfaction |
|---|---:|
| Baggage Handling | **85.4%** |
| Inflight Service | **81.8%** |
| Online Boarding | **70.9%** |
| On-board Service | **70.2%** |
| Leg Room Service | **68.6%** |

### Main Improvement Areas

| Service Attribute | Satisfaction |
|---|---:|
| Inflight Entertainment | **48.6%** |
| Seat Comfort | **48.8%** |
| Departure / Arrival Time Convenience | **50.3%** |
| Ease of Online Booking | **50.6%** |
| Gate Location | **51.8%** |

### 💡 Business Insight

Operational services such as baggage handling and inflight service perform strongly.

However, two attributes directly associated with the **premium travel experience — Inflight Entertainment and Seat Comfort — are among the lowest-rated services**.

This indicates that the main improvement opportunity is not basic service execution, but the perceived quality of the premium onboard experience.

---

# 🗺️ 2. Satisfaction Map

A **Satisfaction Map** was created by evaluating service attributes through two dimensions:

- **Importance**
- **Customer Satisfaction**

This allows service attributes to be prioritized beyond simply looking at average scores.

### Key Example

**Inflight Entertainment**

- Importance: **0.582**
- Satisfaction: **48.6%**

Inflight Entertainment combines relatively **high importance with low satisfaction**, making it one of the most strategically important improvement areas.

In comparison, services such as Wi-Fi and On-board Service have both higher importance and stronger satisfaction levels.

### 💡 Business Insight

A low satisfaction score alone does not automatically justify investment.

The highest priority should be given to services where:

> **Customer Importance is High + Satisfaction is Low**

This makes **Inflight Entertainment a stronger investment priority than some other low-scoring attributes**.

---

# 🛫 3. Class vs Flight Distance

Flight-distance distribution changes significantly across passenger classes.

| Class | Short Flight | Medium Flight | Long Flight |
|---|---:|---:|---:|
| Business | 21.8% | 21.9% | **56.3%** |
| Economy | **43.7%** | **44.2%** | 12.1% |
| Economy Plus | **45.4%** | **41.5%** | 13.1% |

### 💡 Business Insight

More than half of Business Class passengers are concentrated in **long-distance flights**.

Economy and Economy Plus passengers, on the other hand, are mainly concentrated in short and medium-distance flights.

This means that improvements to:

- Seat Comfort
- Inflight Entertainment
- Long-haul onboard experience

may create greater value when prioritized specifically for **long-haul Business Class passengers**.

---

# 👥 4. Age & Gender Segmentation

Four customer-experience criteria were compared across age and gender groups:

- Inflight Wi-Fi
- Inflight Entertainment
- Seat Comfort
- Cleanliness

### Gender Comparison

| Metric | Female | Male |
|---|---:|---:|
| Inflight Wi-Fi | 3.63 | 3.61 |
| Inflight Entertainment | 2.82 | 2.83 |
| Seat Comfort | 2.88 | 2.86 |
| Cleanliness | 3.48 | 3.49 |

### 💡 Business Insight

Male and female satisfaction scores are almost identical.

Therefore, **gender does not appear to be a strong differentiating variable for customer experience**.

Age segmentation provides more meaningful differences.

---

# 🎯 5. Age-Based Customer Experience

The age analysis shows that some service problems become more visible within specific customer groups.

Young passenger segments generally report lower scores for:

- Inflight Entertainment
- Seat Comfort

Middle-aged groups show relatively stronger satisfaction levels.

Very small older-age segments also show low values; however, these results should be interpreted carefully because of limited sample sizes.

### 💡 Business Insight

Customer-experience personalization should focus more on **age and travel behavior** than gender.

For younger passengers, potential improvement areas include:

- More relevant entertainment content
- Mobile-first entertainment access
- Better digital experience
- Improved onboard comfort

---

# ⏱️ 6. Departure / Arrival Time Convenience

Flight-distance groups were compared using:

- Departure / Arrival Time Convenience
- Average Departure Delay
- Average Arrival Delay

| Flight Type | Convenience Score | Departure Delay | Arrival Delay |
|---|---:|---:|---:|
| Short Flight | 54.8 | 14.22 min | 14.87 min |
| Medium Flight | **57.2** | **15.65 min** | **15.99 min** |
| Long Flight | **52.8** | 14.58 min | 14.67 min |

### 💡 Business Insight

Medium-distance flights have the **highest average delays**, but they also generate the **highest convenience satisfaction score**.

Therefore:

> **Operational delay alone does not explain customers' perception of schedule convenience.**

Other factors may also influence customer perception, including:

- Departure time
- Arrival time
- Connection availability
- Schedule flexibility
- Overall travel planning convenience

This suggests that schedule convenience should be analyzed separately from pure operational delay performance.

---

# 🔗 Cross-Analysis Insight

The strongest insight appears when multiple analyses are connected.

### Business Class
⬇  
**56.3% of passengers travel on long-distance flights**

### Business Class Satisfaction
⬇  
**Seat Comfort and Inflight Entertainment are among the lowest-rated services**

### Satisfaction Map
⬇  
**Inflight Entertainment also has relatively high customer importance**

### Business Conclusion

The largest customer-experience opportunity appears to be:

> **Improving the premium onboard experience of long-haul Business Class passengers.**

This conclusion is stronger than evaluating any individual Pivot Table alone because it combines:

**Customer Segment + Flight Behavior + Satisfaction + Service Importance**

---

# 🚀 Business Recommendations

## 1. Improve Inflight Entertainment

Inflight Entertainment should be treated as a strategic customer-experience priority because it combines low satisfaction with relatively high customer importance.

Possible actions:

- Expand entertainment content variety
- Improve mobile/device accessibility
- Develop age-based content categories
- Improve entertainment system usability

---

## 2. Improve Seat Comfort

Seat Comfort is consistently one of the lowest-rated premium experience attributes.

Possible actions:

- Analyze satisfaction by aircraft and seat configuration
- Conduct ergonomic customer research
- Prioritize long-haul Business Class aircraft
- Track comfort scores after improvements

---

## 3. Focus Premium Improvements on Long-Haul Flights

Because **56.3% of Business Class passengers are long-haul passengers**, premium-experience improvements should initially focus on long-distance routes.

This approach may generate greater customer value than applying the same investment equally across all flight types.

---

## 4. Use Age-Based Segmentation

Gender differences are limited, while age segments show greater variation.

Future customer-experience initiatives should therefore consider:

- Age
- Flight Distance
- Travel Class
- Travel Type

together rather than relying on gender-based segmentation alone.

---

## 5. Investigate Schedule Convenience Beyond Delays

Departure and arrival delays do not fully explain schedule-convenience satisfaction.

Future analysis should include:

- Flight schedule
- Departure time
- Arrival time
- Connection structure
- Route characteristics

to identify the real drivers of customer schedule perception.

---

# 🛠️ Tools & Methods

### Microsoft Excel

- Pivot Tables
- Data Filtering
- Conditional Analysis
- Customer Segmentation
- Satisfaction Scoring
- Satisfaction Mapping
- Descriptive Statistics
- Business KPI Analysis
- Data Visualization

### Analytical Approach

- Customer Experience Analytics
- Segmentation Analysis
- Service Performance Analysis
- Importance vs Satisfaction Analysis
- Cross-Analysis
- Business Insight Generation
- Action-Oriented Recommendations

---

# 📂 Project Files

```text
04-airline-customer-satisfaction-analysis/
│
├── README.md
├── Airline_Customer_Satisfaction_Analysis.xlsx
└── Airline_Customer_Satisfaction_Executive_Deck.pdf
