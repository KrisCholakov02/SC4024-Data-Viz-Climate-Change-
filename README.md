# 🌍 SC4024: The Power of Visualizing Our Planet: From Data to Saving the Environment

## 📌 Project Overview
This project focuses on creating engaging and interactive **data visualizations** that highlight the relationship between **human actions and their environmental impact**. Through a carefully designed sequence of visual storytelling, the project covers:
1. **Human Progress vs. Environmental Impact** – Examining the correlation between industrial development and environmental degradation.
2. **Causes of Climate Change** – Visualizing the distribution and growth of climate change sources.
3. **Global Consequences** – Understanding the wide-ranging effects of climate change and their feedback into human life.
4. **A Sustainable Future** – Tracking the progress of sustainability efforts and evaluating their effectiveness.

## 🎨 Novelty & Key Contributions
This project introduces several **novel visualizations** to enhance user engagement and insight discovery:
- **Custom SVG-based Animated Plots**:  
  - **Sea Level Rise Visualization**  
  - **Antarctic Ice Mass Change Visualization**
- **4-Axis Correlation Plot**: Demonstrates the impact of human progress on climate change using multiple datasets.
- **Custom World Maps**: Overcomes limitations of existing libraries to create a **split bubble map chart** for illustrating each country’s fossil fuel dependency.
- **3D Water Column Chart**: Displays temperature changes across ocean depths using segmented 3D prisms.
- **Bubble Time Plot**: Maps climate-related events over time, highlighting their impact on populations.

## 🛠️ Technologies & Tools Used
This project was built using a combination of **Python-based visualization and data processing libraries**:
- **Data Processing & Analysis**:
  - `pandas`, `numpy` – for data cleaning, aggregation, and transformation.
- **Data Visualization**:
  - `matplotlib`, `seaborn` – for static visualizations.
  - `plotly` – for interactive and animated charts.
- **Geospatial Data Visualization**:
  - `geopandas`, `geopy` – for processing geographic data.
  - **Natural Earth** dataset integration for improved mapping capabilities.

## ⚙️ Technical Challenges & Innovations
Creating **high-quality, interactive, and meaningful** visualizations required overcoming several challenges:
1. **Interactive Animation**:  
   - Used **Plotly’s frame-based animation** techniques for smooth data transitions.  
   - Built **play/pause controls** to enhance user interactivity.
2. **Multi-Dataset Integration**:  
   - Combined **climate, geographic, and socio-economic data** from multiple sources.  
   - Applied data **merging, aggregation, and transformation** techniques.
3. **Geospatial Visualization**:  
   - Integrated **Natural Earth** maps and **GeoPandas** to display country-level environmental statistics.
   - Enhanced clarity by using **color gradients, size variations, and text annotations**.
4. **Mathematical Data Scaling**:  
   - Implemented **square root and quadratic transformations** to ensure proportional representation in area-based plots.

## 📊 Key Visualizations
### 🌊 **Sea Level Rise & Antarctic Ice Mass Change (Animated Plots)**
- Custom SVG-based plots illustrating **sea level rise** and **ice mass reduction** over time.
- Implemented **frame-based animation** for dynamic storytelling.

### 🌍 **World Energy Dependency (Bubble Map)**
- A **split bubble map chart** demonstrating **fossil fuel dependency** across countries.
- Overcame **Matplotlib and Plotly limitations** by using **Natural Earth maps**.

### 🌡️ **3D Ocean Temperature Change Chart**
- A **3D segmented water column** displaying decade-by-decade ocean temperature variations.
- Each depth section is rendered as a **3D prism**, enhancing depth perception.

### 🏆 **Climate Impact Timeline (Bubble Time Plot)**
- Connects **major climate events (droughts, storms, etc.)** to their **human impact**.
- Annotated with key **historical climate-related disasters**.

## 📚 Data Sources
This project utilizes reliable, globally recognized datasets:
1. **Our World in Data** – [https://ourworldindata.org](https://ourworldindata.org)
2. **National Snow and Ice Data Center (NSIDC)** – [https://nsidc.org/ice-sheets-today/melt-data-tools](https://nsidc.org/ice-sheets-today/melt-data-tools)
3. **Natural Earth (Geospatial Data)** – [https://www.naturalearthdata.com](https://www.naturalearthdata.com/downloads/110m-cultural-vectors)
4. **World Ocean Atlas (NOAA)** – [https://www.ncei.noaa.gov/products/world-ocean-atlas](https://www.ncei.noaa.gov/products/world-ocean-atlas)

## 🚀 How to Run the Project
### 1️⃣ Install Dependencies
Ensure you have Python and the required libraries installed. You can set up the environment using:
```bash
pip install pandas numpy matplotlib seaborn plotly geopandas geopy
```
### 2️⃣ Run Visualization Scripts
Execute the Python scripts or Jupyter Notebooks to generate visualizations:
```bash
python visualization_script.py
```
or
```bash
jupyter notebook
```
and open the relevant notebooks.

## 🏆 Conclusion
This project leverages **advanced data visualization techniques** to uncover key **climate change insights**. By integrating **interactive animations, 3D visualizations, and geospatial data**, it provides an engaging way to **explore environmental challenges and trends**.

### 📢 Want to Learn More?
Check out the full **report** in 📄 `Report.pdf` for a **detailed breakdown** of methodologies, technical implementations, and insights.
