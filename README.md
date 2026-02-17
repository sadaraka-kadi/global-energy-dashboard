
# Global Energy Transition Dashboard
Interactive Tableau dashboard analyzing global energy transition trends.

## Data
Multi-country, multi-year energy data by source.

### Data Scale
- **Unit**: Terawatt-hours (TWh)
- **1 TWh** = 1,000,000,000 kWh (1 billion kilowatt-hours)

## Methods
- Data cleaning & feature engineering in Python
- Energy dependency and transition metrics
- Interactive dashboards in Tableau Public

# Global Renewable Energy Story

An interactive Tableau data visualization project exploring global energy consumption patterns, renewable energy growth, and the transition from fossil fuels to clean energy sources across continents and countries from 1970 to 2025.

## Project Overview

This Tableau story provides comprehensive insights into:

- **Global energy consumption trends** spanning over five decades
- **Renewable vs. fossil fuel adoption** patterns across continents
- **Solar and wind energy growth trajectories** and acceleration periods
- **Country-level comparisons** identifying energy leaders and fast-growing markets
- **Continental energy mix evolution** showing the shift toward sustainability

The project consists of multiple interactive dashboards and visualizations that tell the story of humanity's energy transition.

##  Key Features

### Main Story: Global Energy Overview

- **Energy Growth Visualization**: Temporal comparison showing how energy consumption has evolved across three key periods (Pre-1995, 1995-2010, 2011-Latest)
- **Top Energy Consumers**: Ranking of countries by total energy consumption
- **Energy Source Leaders**: Individual rankings for renewable, fossil, and nuclear energy
- **Continental Comparisons**: Regional patterns in energy mix and growth rates

## Visualizations Included

| Sheet Name | Visualization Type | Purpose |
|------------|-------------------|---------|
| Energy Growth | Grouped Bar Chart | Show energy consumption evolution across three periods |
| Top Energy | Horizontal Bar Chart | Rank countries by total energy consumption |
| Top Renewable | Horizontal Bar Chart | Identify renewable energy leaders |
| Top Fossil | Horizontal Bar Chart | Show fossil fuel dependency patterns |
| Top Nuclear | Horizontal Bar Chart | Display nuclear energy capacity leaders |
| Solar Energy Growth Rates | Heat Map | Visualize solar growth acceleration over time |
| Wind Energy Growth Rates | Heat Map | Track wind energy expansion patterns |
| Solar vs Wind Timeline | Dual-Axis Line Chart | Compare growth trajectories of both technologies |
| Energy Mix by Continent | Stacked Bar Chart | Show renewable vs. fossil composition by region |
| Growth Rate Comparison | Scatter Plot | Analyze solar vs. wind growth dynamics by country |

## 🗂️ Data Sources

**Dataset**: Global Energy Transition Data (1970-2025)

**Key Metrics**:
- Total Energy Consumption (TWh)
- Fossil Fuel Energy (TWh)
- Renewable Energy (TWh)
- Nuclear Energy (TWh)
- Solar Energy (TWh)
- Wind Energy (TWh)
- Growth Rates (Year-over-Year %)

**Geographic Coverage**: 
- 200+ countries
- 6 continents
- Regional and continental aggregations

**Temporal Coverage**: 1970-2025 (with projections for recent years)

## 💡 Key Insights

### Global Trends

🔸 **Energy consumption has more than doubled** since 1995, with Asia experiencing the most dramatic growth

🔸 **USA and China dominate** global energy consumption, together accounting for over 40% of worldwide usage

🔸 **Renewable energy has grown exponentially** since 2010, driven primarily by solar and wind technologies

## 🔄 Future Enhancements

### Planned Features

- [ ] Add per-capita energy consumption metrics
- [ ] Include energy intensity (energy per GDP) analysis
- [ ] Integrate carbon emissions data
- [ ] Add cost analysis (LCOE - Levelized Cost of Energy)
- [ ] Create mobile-optimized dashboard layouts
- [ ] Add predictive models for future energy mix
- [ ] Include hydroelectric and geothermal energy sources
- [ ] Add policy timeline overlays (Paris Agreement, etc.)

### Data Updates

- [ ] Automate data refresh from public sources
- [ ] Add real-time or quarterly data updates
- [ ] Expand historical data pre-1970 where available
- [ ] Include more granular geographic data (states/provinces)

## Tools
Python, Pandas, Tableau Public
