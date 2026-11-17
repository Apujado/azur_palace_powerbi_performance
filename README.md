# 🏨 Azur Palace | Hotel Performance Dashboard

> Power BI dashboard for a 5-star hotel group, designed to monitor guest satisfaction, hotel performance and regional benchmarking.

## 📌 Overview

Azur Palace is a Business Intelligence project focused on analysing the overall performance of a hotel portfolio. It transforms guest review data into actionable KPIs to support strategic decisions across the group.

The project delivers clear business value by enabling:

- faster visibility into the health of each hotel,
- quick identification of underperforming sites,
- regional and operational benchmarking,
- tracking of satisfaction trends over time,
- prioritisation of improvement actions on the most impactful levers.

## 🔎 Key insights already visible

The dashboard helps surface the most relevant operational signals:

- global median satisfaction score for the group,
- strongest and weakest regions,
- hotels above and below the median benchmark,
- criteria driving customer satisfaction,
- year-over-year changes to detect positive or negative trends.

## 🏗️ Data model

The semantic model follows a star schema with:

- `FACT_Reviews` : customer reviews and detailed scores
- `DIM_hotel` : hotel metadata and location
- `DIM_users` : guest profiles and segmentation
- `Dim_Date` : date table for Time Intelligence
- `DAX` : business KPIs and measures
- `Score Hotels` : multi-criteria performance analysis

Data sources include `Assests/Dataset/hotels.csv`, `reviews.csv` and `users.csv`.

## 📊 Report pages

The project currently includes 2 built pages and 2 pages under development:

1. `Summary` — overview and macro KPIs
2. `Hotel Performance` — performance by hotel and region
3. `Granular Customer Voice` — detailed customer feedback analysis
4. `Hotel_Details` — detailed drill-down by hotel

## 🎯 Core KPIs

The DAX layer covers:

- global median score,
- review volume,
- share of hotels above the median,
- YoY comparison,
- regional benchmarking,
- top satisfaction drivers.

## 🤖 Governance and workflow

The project follows a modern Power BI workflow:

- `PBIP` + `TMDL` structure,
- Git/GitHub versioning,
- standardised DAX measures,
- quality review supported by an AI assistant (Copilot / MCP).

## 🛠️ Tech stack

- Power BI Desktop / `.pbip`
- DAX and Power Query
- TMDL
- Git / GitHub
- VS Code
- AI assistant / MCP (Copilot)

## 🚀 Getting started

1. Open `Azur_Palace.pbip` in Power BI Desktop.
2. Check the files under `Assests/Dataset`.
3. Load the semantic model if needed.
4. Explore the `Summary` and `Hotel Performance` pages.

Azur Palace demonstrates the value of BI tools in transforming raw hotel data into concrete decision-making insights, highlighting the strengths, weaknesses and improvement opportunities of the group.