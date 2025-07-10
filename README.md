# 🚚 Transportation Route Optimization & Cost Analysis

This project builds an intelligent tool that identifies the most cost-effective transportation routes while minimizing fuel usage, delivery time, and carbon emissions. The optimization model is powered by Google OR-Tools and visualized in Power BI and Python mapping tools.

![Project Status](https://img.shields.io/badge/status-in_progress-yellow)

## 🔧 Tools Used
- Python, Pandas, NumPy
- NetworkX
- Google OR-Tools (TSP/VRP Solver)
- Folium / Plotly (Geospatial Mapping)
- Excel/CSV (for input/output)

## 🎯 Features
- Optimal route selection based on delivery points and vehicle constraints
- Total cost calculator (fuel, distance, time)
- CO₂ impact estimator by route
- Load balancing across available vehicles
- Interactive route maps
- Power BI dashboard with summary metrics

## 📁 Data Structure

### `depots.csv`
| depot_id | lat      | lon      | capacity |
|----------|----------|----------|----------|
| D1       | 30.2672  | -97.7431 | 2000     |

### `customers.csv`
| customer_id | lat      | lon      | demand | time_window_start | time_window_end |
|-------------|----------|----------|--------|-------------------|-----------------|
| C1          | 30.3001  | -97.7000 | 250    | 9:00              | 12:00           |

## 📊 Output Examples

- 📦 Route table: customer sequence, ETA, load
- 💰 Cost metrics: fuel per km, route cost, emissions
- 🗺️ Map: optimized route by vehicle
- 📈 Power BI: service time, CO₂, fuel burn, total cost

## 📷 Visuals (to be added)
*Insert screenshots of map, charts, dashboard*

## 🔄 Next Steps
- Add multi-day routing support
- Include road traffic delay modeling
- Build integration with live GPS data feeds

## 👤 Author
Tigris Mendez  
UT Austin | Supply Chain & Analytics  
[LinkedIn](https://www.linkedin.com/in/...)

