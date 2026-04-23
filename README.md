# Spatio-temporal-Analysis-of-Unemployment-in-France
## Objective

This project analyzes the spatial and temporal evolution of unemployment rates across French departments in order to highlight regional disparities and long-term trends.

---

## Data Sources

- INSEE: unemployment statistics by department and year  
- IGN: geographical boundaries of French departments  

Data were merged using department codes to build a consistent spatio-temporal dataset.

---

## Data Processing

- Data cleaning and formatting of departmental identifiers  
- Handling missing values  
- Merging statistical and geographical datasets  
- Construction of a spatio-temporal panel dataset  

---

## Methodology

- Geographical mapping using department-level GeoJSON  
- Computation of national averages over time  
- Analysis of inter-departmental variance  
- Visualization using interactive choropleth maps (Plotly)

---

## Key Results

### Spatial structure
Unemployment shows a strong and persistent spatial pattern, with higher rates concentrated in the North, South, and parts of the West of France. These disparities remain stable over time.

---

### Temporal evolution
The national unemployment rate follows a cyclical pattern, with two major peaks observed around 1995 and 2015, reflecting macroeconomic cycles.

---

### Regional disparities
Inter-departmental variance peaks around 1999, before stabilizing around lower values, suggesting a partial homogenization of territorial differences.

---

## Main Insight

Unemployment in France is primarily driven by **structural spatial factors**, while temporal fluctuations affect all regions similarly without fundamentally changing regional inequalities.

---

## Visualization

![Unemployment map](figures/chomage_map.png)

---

## Technologies

- Python  
- Pandas  
- Plotly (data visualization library)
- INSEE data (French statistical institute)
- IGN data (French geographical institute)

---

## Project Structure
- data/ → raw and processed datasets  
- notebooks/ → data analysis and visualization  
- figures/ → exported maps and plots  
- src/ → reusable Python functions  
- README.md → project documentation 
