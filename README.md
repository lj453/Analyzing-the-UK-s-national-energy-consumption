# Analyzing-the-UK-s-national-energy-consumption
 Conducted statistical research, quantitative analysis, regression,  and visualizations. Time-series forecasting based on historical datasets of national energy usage was compared  using predictive machine learning models like ARIMA and LSTM

## Overview

The UK’s energy consumption is primarily driven by four sectors:

- **Transportation**
- **Industrial**
- **Domestic**
- **Services**

On average, the transportation and domestic sectors account for over 60% of the total energy usage in the nation, while the services sector consumes the least amount of energy in comparison. The industrial sector has shown a steady decline in energy consumption over the years.

### Total Energy Consumption (2021)
In 2021, the UK consumed 128,213.5 thousand tonnes of oil equivalent energy, excluding consumption from sectors outside of the primary four.

### Key Findings

- **Decline in Consumption**: Over the past two decades, there has been a gradual decline in the UK’s energy consumption, with the lowest usage recorded in 2020, primarily due to the impact of the COVID-19 pandemic.
  
- **Sectoral Impact of COVID-19**: The pandemic caused significant reductions in energy usage, especially in the transportation and services sectors due to government-imposed lockdowns and restrictions.

- **Energy Sources**: 
  - In the domestic sector, natural gas consumption is at least twice as high as electricity consumption.
  - The services sector mainly relies on natural gas and electricity, with 67.2% of energy usage coming from commercial services.
  - Industrial energy consumption has decreased over the years, closely related to the decline of coal industries and increased offshore production.

- **Transportation Sector**: 
  - On average, transportation consumes 38% of the total energy, with road petroleum making up 80.7% of this sector's energy consumption.
  - The correlation between the number of newly registered vehicles and road fuel consumption suggests that fossil fuel-based vehicles still dominate the market.

### Policy Recommendations

- **Domestic Sector**: Focus on reducing reliance on natural gas and promote the adoption of renewable energy sources like bioenergy. Policies such as the Energy Performance Certificate (EPC) can help improve energy efficiency in buildings.
  
- **Services Sector**: Encourage public administrations to enhance energy efficiency, especially during economic downturns, as their energy consumption tends to increase in these periods.
  
- **Industrial Sector**: Support policies that align with the UK’s net-zero targets to encourage industries to adopt energy-efficient and eco-friendly alternatives, further reducing both energy consumption and emissions.

- **Transportation Sector**: Promote the use of electric vehicles and compressed natural gas (CNG) engines, and improve public transport and infrastructure for cycling and walking to reduce overall energy consumption in this sector.

## Forecasting Future Energy Demand

To better understand future energy demand, two forecasting models were explored:

- **ARIMA Model**: A statistical forecasting method that, despite being interpretable, showed limitations due to white noise in the data and performed poorly on future predictions.
  
- **LSTM Model**: A machine learning model that outperformed ARIMA in terms of accuracy for energy consumption predictions.

Due to the limitations of the ARIMA model, particularly with energy data, LSTM was adopted as the primary model for forecasting future energy consumption in the UK.

## Conclusion

The analysis provides insights into the energy consumption trends of the UK, helping policymakers shape better energy policies for a sustainable future. It emphasizes the importance of improving energy efficiency, diversifying energy sources, and enhancing infrastructure to meet the UK's energy demands while working towards environmental sustainability.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

