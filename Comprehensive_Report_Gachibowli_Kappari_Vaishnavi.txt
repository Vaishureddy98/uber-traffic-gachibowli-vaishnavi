
# UBER TRAFFIC FORECASTING - GACHIBOWLI HYDERABAD
## Comprehensive Peak Hour Analysis Report - By Kappari Vaishnavi

Date: 11-09-2026
Junction: Gachibowli, Hyderabad - IT Corridor

### 1. EXECUTIVE SUMMARY
Peak hours at 9-10 AM and 18-19 PM with threshold 564 vehicles (Mean+Std). Max 735 vehicles at 9 AM and 725 at 6 PM.

### 2. IDENTIFIED PEAK HOURS
 Hour  Avg_Vehicles  Median  Max
    9    735.044444   743.5  946
   10    716.344444   727.5  944
   18    725.111111   689.0  949
   19    700.233333   665.5  949

- Morning Peak: 9 AM - 735 avg - Office start
- Evening Peak: 6 PM (18) - 725 avg - Office end, highest congestion
- Secondary: 10 AM (716) & 7 PM (700)

### 3. PATTERNS & VARIATIONS
- Day Variation: Weekdays Mon-Fri 10% higher than weekend. Friday evening highest (heatmap Hour vs Day).
- Month Variation: Summer higher traffic, rainy month congestion higher per vehicle (heatmap Hour vs Month).
- Weekday vs Weekend: Weekday 580, Weekend 520 avg. Same peak hours due to IT hub.

### 4. INFLUENCING FACTORS
- Temperature: Negative correlation
- Is_Rainy: +45 vehicles, speed reduction 15 km/h
- Is_Event: +60 vehicles - Gachibowli stadium events
- Is_Holiday: -30 vehicles but compensated by events

### 5. ACTIONABLE INSIGHTS & RECOMMENDATIONS
1. Signal Timing: Increase green time 30% at Gachibowli junction 9-10 AM and 6-8 PM
2. Stagger Office: 8:30, 9:30, 10:30 timings for IT companies to split peak
3. Rainy Protocol: Extra police during rainy peaks - congestion +12%
4. Event Management: Divert via ORR service road 5-9 PM, pre-alert Uber surge
5. Public Transport: Increase metro frequency during 18-19 hr, encourage carpool
6. Uber Strategy: 1.5x surge during 9AM & 6PM peaks, pre-position cabs at DLF, Wipro circle
7. Long-term: Underpass at Gachibowli-ORR for 6PM mitigation

### 6. VISUALIZATIONS
- Peak identification line chart, Weekday vs Weekend, Heatmap Hour vs Day, Hour vs Month, Scatter Temp vs Vehicles, Line External Factors

### 7. CONCLUSION
Gachibowli bimodal IT peak pattern. Evening 6-7 PM critical. External factors amplify peaks.
Files at: github.com/Vaishureddy98/uber-traffic-gachibowli-vaishnavi
