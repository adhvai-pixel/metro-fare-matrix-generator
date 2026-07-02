# 💰 Interactive Fare Matrix Generation System

> **Internship Project Showcase**  
> **Note:** The source code is not included in this repository as it was developed during an internship and is subject to confidentiality. This repository showcases the project's functionality, methodology, and outputs.

---

# 📌 Overview

The **Interactive Fare Matrix Generation System** is a web-based application developed to automate the creation, visualization, and management of metro fare matrices.

Built using **HTML, CSS, and JavaScript**, the application enables users to configure fare rules, manage station information, generate station-to-station fare matrices, visualize fare distributions using heat maps, and export the generated data for further analysis.

The system was designed to simplify fare calculation processes while reducing manual effort and improving accuracy.

---

# 🎯 Objectives

- Automate station-to-station fare matrix generation.
- Provide configurable fare rules without modifying source code.
- Support manual and bulk station data entry.
- Visualize fare distributions using a color-coded heat map.
- Export generated fare matrices in CSV format.

---

# 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- CSV Export

---

# 📂 System Workflow

```text
Configure Fare Rules
          │
          ▼
Add Station Information
(Manual / Bulk / Load All)
          │
          ▼
Generate Fare Matrix
          │
          ▼
Display Fare Table
          │
          ▼
Heat Map Visualization
          │
          ▼
Export CSV
```

---

# 📖 System Modules

## 1. User Interface Design

A responsive and user-friendly interface was developed using **HTML** and **CSS**.

The interface allows users to:

- Configure fare rules
- Manage station information
- Generate fare matrices
- Visualize fare distributions
- Export generated data

JavaScript provides dynamic interaction and real-time fare calculations.

---

## 2. Fare Rule Configuration

The application allows fare rules to be configured directly through the interface without modifying the source code.

Users can configure parameters such as:

- Base fare
- Incremental fare
- Distance-based fare values
- Other fare calculation settings

This makes the application flexible for different fare structures.

---

## 3. Station Data Management

The system supports multiple methods for entering station information.

### Manual Station Entry

Users can enter individual station names through input fields.

This method is suitable when only a few stations need to be added or updated.

---

### Bulk Station Import

Multiple station names can be pasted into a text area.

The application automatically:

- Separates station names
- Validates the input
- Stores the stations for fare generation

This significantly reduces manual effort for large datasets.

---

### Load All Stations

A single-click feature automatically loads all predefined metro stations.

This enables users to quickly generate fare matrices for the complete metro network without manually entering station names.

---

## 4. Automated Fare Matrix Generation

Once station data and fare rules have been configured, the application automatically generates a complete station-to-station fare matrix.

JavaScript algorithms calculate fares between every possible station pair based on the configured fare rules.

The generated fare matrix is displayed in a structured table for easy verification.

---

## 5. Heat Map Visualization

To improve fare analysis, the generated matrix is visualized as a color-coded heat map.

### Color Representation

| Color | Fare Range |
|--------|------------|
| 🟢 Green | Low fares |
| 🟡 Yellow | Moderate fares |
| 🟠 Orange | High fares |
| 🔴 Red | Very high fares |

The heat map enables users to quickly identify:

- Low-cost routes
- High-cost routes
- Fare distribution patterns
- Network-wide fare trends

---

## 6. CSV Export

The application allows users to export the generated fare matrix as a CSV file.

The exported file can be opened using spreadsheet software such as:

- Microsoft Excel
- Google Sheets
- LibreOffice Calc

This enables further analysis, sharing, and record keeping.

---

# 📷 Sample Features

✅ Configure fare rules

✅ Add stations manually

✅ Import stations in bulk

✅ Load complete metro station list

✅ Generate station-to-station fare matrix

✅ Heat map visualization

✅ CSV export

---

# 📊 Results

The Interactive Fare Matrix Generation System successfully generated a complete fare matrix for a metro network consisting of **162 stations**.

The system automatically applied the configured fare rules and displayed the results in both tabular and graphical formats.

### Key Observations

- Fare values increased progressively with travel distance.
- Adjacent stations generally had fares ranging from **₹10–₹20**.
- Medium-distance journeys typically ranged from **₹30–₹50**.
- Long-distance journeys ranged from **₹60–₹100**.
- Diagonal cells contained **₹0**, representing travel from a station to itself.
- The generated fare matrix remained symmetrical and consistent across all station combinations.

---

## Heat Map Analysis

The heat map improved readability by representing fare values with different colors.

| Fare Level | Color |
|------------|-------|
| Low | 🟢 Green |
| Moderate | 🟡 Yellow |
| High | 🟠 Orange |
| Very High | 🔴 Red |

This visualization enabled quick identification of fare trends without manually inspecting individual values.

---

# 📈 Project Highlights

- Automated fare matrix generation
- Dynamic fare rule configuration
- Interactive user interface
- Bulk station data processing
- Heat map visualization
- CSV export functionality
- Efficient fare analysis
- Reduced manual calculation effort

---

# 📚 Concepts Demonstrated

- JavaScript DOM Manipulation
- Dynamic UI Design
- Data Processing
- Matrix Generation
- Fare Calculation Logic
- Heat Map Visualization
- CSV File Generation
- User Interface Design
- Data Validation

---

# 📸 Repository Structure

<img width="1217" height="652" alt="image" src="https://github.com/user-attachments/assets/22dbd58e-ea89-43eb-934f-5f176eb77979" />
<img width="532" height="677" alt="image" src="https://github.com/user-attachments/assets/67779240-79be-4e9a-b4fd-d041f7fa592e" />
<img width="515" height="312" alt="image" src="https://github.com/user-attachments/assets/3f76b954-3651-4d5c-8cb1-d7473d792f14" />
<img width="507" height="332" alt="image" src="https://github.com/user-attachments/assets/bf10a48b-d808-4ab7-a098-863a7d99bd79" />
<img width="345" height="607" alt="image" src="https://github.com/user-attachments/assets/780fcc73-932b-4d1f-982e-1ef2c8302629" />
<img width="756" height="423" alt="image" src="https://github.com/user-attachments/assets/f50384a9-9204-4748-80e2-32bbbe9713a0" />







# 🔒 Disclaimer

This repository is intended solely to showcase internship work.

The original implementation and source code are **not included** because they were developed during an internship and are subject to confidentiality.

Only the project overview, methodology, screenshots, outputs, and documentation are shared for portfolio purposes.
