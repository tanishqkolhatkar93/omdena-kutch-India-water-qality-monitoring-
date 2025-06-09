
# 🌊 Water Quality Monitoring – Kutch (Omdena Project)

This is a collaborative Omdena project aimed at monitoring and predicting water quality in the Kutch region using satellite data from **Google Earth Engine**. By analyzing environmental and geographical parameters, the project visualizes and forecasts water quality, helping stakeholders make informed decisions.


---

## 📁 Project Structure

```
├── LICENSE
├── README.md          <- Top-level overview for developers and collaborators.
├── original           <- Source code from the original Omdena challenge (reference only).
├── reports            <- Final reports/results of the project.
│   └── README.md
├── src
│   ├── data           <- Datasets used and collected.
│   ├── docs           <- Task documentation, meeting notes, workflow diagrams.
│   ├── references     <- Research papers, manuals, data dictionaries.
│   ├── tasks          <- Master folder for individual task contributions.
│   ├── visualizations <- Visual dashboards and data visualizations.
│   └── results        <- Final modeling and analysis results.
```

---

## ✅ Contribution Guidelines

📌 Before contributing, **read this carefully**:

- **Create a task**:
  - Go to the `tasks/` folder.
  - Create a new folder using this naming format:  
    `task-n-taskname` (e.g., `task-1-data-collection`, `task-2-model-training`)
  - Add a `README.md` in your task folder with:
    - Task overview
    - Goals
    - A **contribution table** listing contributors and their files.

- **If you're contributing to an existing task**:
  - Add your work in the relevant task folder.
  - Update that task's `README.md` contribution table with:
    - Your file name
    - Description
    - Contributor name
    - File link (optional)

- **File naming**:
  - Use clear, self-explanatory names for Jupyter notebooks, Python files, data files, etc.
  - Avoid creating folders outside the `tasks/` directory unless approved.

---

## 🌐 Dashboard Filters (For Water Body Selection)

You can filter water quality predictions based on:

- **Water Body Type**
- **Area of Interest**
- **Latitude**: `23.0063`
- **Longitude**: `72.6026`
- **Start Date**: Select between `2019-01-01` or `2021-11-01`
- **End Date**: Select between `2019-01-15` or `2021-12-31`

📝 **Note 1**: Date range must be between **15 days** and **3 months**.  
📝 **Note 2**: Shorter or longer ranges will not generate results.

---
## Project Demo  

![](Screenshot%202025-06-09%20112435.png)

## 🎯 Project Goal

The goal of this project is to build a comprehensive system to monitor water quality in Kutch by:

- Collecting and preprocessing remote sensing data via Google Earth Engine.
- Visualizing spatial and temporal water quality changes.
- Predicting water quality using machine learning models.
- Creating an interactive dashboard for insights and decision-making.

---

If you're a contributor or team member, ensure you **stick to the structure** and **maintain clarity and traceability** in your contributions. 💧
