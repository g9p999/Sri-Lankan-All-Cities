# 🇱🇰 Sri Lanka Postal Department – Cities Dataset

This repository contains a cleaned, structured, and multi-format dataset of **Sri Lankan postal cities**, including their names, short codes, and postal codes.
It is designed for developers, researchers, and organizations that need standardized postal location data for Sri Lanka.

---

## 📁 Files Included

### **1. `postal_dep_cities.json`**

* JSON list of all cities
* Includes fields: `name`, `shortName`, `postalCode`

### **2. `postal_dep_cities.csv`**

* CSV version of the dataset
* Can be used in Excel, Sheets, Python, R, etc.

### **3. `postal_dep_cities.txt`**

* Simple text format
* One city per line in the format:

  ```
  Name (ShortName) - PostalCode
  ```

### **4. `postal_dep_cities.xlsx`**

* Excel spreadsheet
* Easy to filter, search, or analyze

---

## 📊 Data Structure

Each record contains:

| Field        | Description                              |
| ------------ | ---------------------------------------- |
| `name`       | City or town name                        |
| `shortName`  | Short code used by Sri Lanka Postal Dept |
| `postalCode` | Official Sri Lankan postal code          |

### Example (`postal_dep_cities.json`):

```json
{
    "name": "Achchuvely",
    "shortName": "(JA)",
    "postalCode": "40150"
}
```

---

## 🛠 How the Data Was Converted

The dataset was originally formatted in JSON and converted into:

* **CSV** using Python `csv` module
* **TXT** using plain text file writing
* **XLSX** using `openpyxl`

If you want to convert or regenerate the dataset yourself, see the sample Python scripts in the repository.

---

## 🚀 Usage Examples

Use this dataset for:

* Postal validation
* Government and logistics apps
* Location lookup tools
* Delivery address systems
* GIS / mapping tools

---

## 🔧 Contributing

Contributions, corrections, and improvements are welcome!
If you want to update a city name or add missing entries:

1. Fork the repo
2. Update the relevant files
3. Submit a pull request

---

## 📜 License

This dataset is released under the **MIT License**.
You may use it freely for personal or commercial projects.


