# Kazakhstan Climate and Grain Yield Dataset (2004–2024)

## Description
This dataset contains:
- Decadal climate data from the **Kazhydromet State Meteorological Service** for four districts of Akmola Region:
  - Arshaly
  - Yereymentau
  - Zhaksı
  - Korgalzhyn
- Time period: **2004–2024**
- Official data from the **Bureau of National Statistics of the Agency for Strategic Planning and Reforms of the Republic of Kazakhstan** on grain and wheat yields, expressed in **centners per hectare (с/ha)**.

## File Structure
- `Аршалы_Final.csv` — climate data for Arshaly district  
- `Ерейментау_Final.csv` — climate data for Yereymentau district  
- `Жаксы_Final.csv` — climate data for Zhaksı district  
- `Коргалжын_Final.csv` — climate data for Korgalzhyn district  
- `Урожайность.csv` — grain and wheat yield
- `HMM_calc.ipynb` file evaluates yield risk regimes from climate data using Hidden Markov Models
- `regression calculator.ipynb` - crop yield forecast based on climate data and regression models
