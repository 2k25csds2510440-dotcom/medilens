# 💊 MediLens

### See. Compare. Save.

MediLens is a full-stack medicine price comparison web application designed to help users search for medicines and compare demonstration prices across different pharmacy options.

The project combines data processing, a FastAPI backend, and a React frontend to create an end-to-end medicine price comparison experience.

---

## ✨ Features

- 🔍 Search medicines by name
- 💊 View medicine dosage and strength
- 💰 Compare pharmacy prices
- 📊 View NPPA ceiling price
- 📉 Calculate price differences and discounts
- 🏪 Display multiple pharmacy options
- 🌐 REST API built with FastAPI
- ⚛️ Interactive React frontend
- 🐍 Python-based data processing pipeline
- 📍 Pharmacy location coordinates for demonstration

---

## 🏗️ Project Architecture

```text
                 NPPA Data
                     │
                     ▼
              PDF Table Extraction
                     │
                     ▼
             Data Cleaning Pipeline
                     │
                     ▼
             Medicine Dataset
                     │
                     ▼
        Synthetic Pharmacy Prices
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
     FastAPI Backend       React Frontend
          │                     │
          └──────────┬──────────┘
                     ▼
             MediLens Web App