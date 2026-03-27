# International_Maritime_Logistics_Project

# Project Overview

This repository contains a comprehensive three-page Power BI reporting suite designed for the Onyx Data DNA Dataset Challenge. The "Maritime Pulse" dashboard provides an executive-level view of global shipping operations, focusing on identifying bottlenecks, monitoring vessel efficiency, and analyzing historical disruption recovery.

# Key Features & Insights

# Executive Operations Pulse: 
. Tracks 15,000 total movements with a +39% year-over-year growth.
. Monitors performance against 2025 strategic goals, highlighting that 48% of movements are currently "Off-Target".
. Identifies 6,049 critical bottlenecks with an average delay of 20.9 days.

# Terminal & Root Cause Analysis: 
. Utilizes a Decomposition Tree to break down bottlenecks by Terminal Name, Vessel Category (Cargo, Container, Tanker, Passenger), and Month.
. Features an Operational Efficiency Scatter Plot comparing "Average Move Days" against "Total Movements" to identify high-variance underperformers.
. Identifies 7 specific terminals requiring immediate intervention to meet risk reduction goals.

# Disruption & Recovery Case Study (Suez Canal):
. Analyzes the impact of the Suez Canal blockage, noting a 104% intensity spike in move days (peaking at 41.16 days).
. Uses Small Multiples to visualize bottleneck intensity across four regional hubs: AMER, APAC, EMEA, and LATAM.
. Tracks the normalization period from 2021 through 2024, showing a 88% reduction in delays from the peak.

# Technical Implementation Tool: 

# Power BI DesktopData Modeling: 
. Star schema with specialized measures for Throughput Efficiency % (currently at 47.42%) and Delay Severity.
. Visuals Used: Decomposition Tree, Small Multiples, Scatter Plots, and Conditional Formatting for status tracking (On Target, At Risk, Critical).

# Project Goal: 
The primary objective of this report is to move from reactive data viewing to proactive operational management. By identifying that 80% of capacity is utilized while 40% of movements result in failures, this dashboard provides the "Pulse Check" necessary for maritime executives to optimize global supply chains.

# Page 01: 
<img width="1332" height="745" alt="Pg 1" src="https://github.com/user-attachments/assets/f2bf5b99-dc0f-4c8a-940d-b137b676c4ef" />

# Page 02:
<img width="1329" height="743" alt="Pg 2" src="https://github.com/user-attachments/assets/c7d6f36f-7134-4161-83ca-4e09051c6de5" />

# Page 03:
<img width="1329" height="748" alt="Pg 3" src="https://github.com/user-attachments/assets/1cbfc7cb-ac6f-4507-8c03-7654ed048155" />
