# Awesome Warfarin Projects

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome open-source projects, research, and resources for Warfarin Projects.

---

## Contents

- [Web Applications](#web-applications)
- [Machine Learning & Research](#machine-learning--research)
- [Related Resources](#related-resources)

---

## Web Applications

*A collection of web-based tools and dashboards for calculating or simulating warfarin dosage.*

- [Vue-Quick-Warfarin-V2](https://github.com/Napatchouli/Vue-Quick-Warfarin-V2) - A Warfarin Web App built with Vue.js to help clinicians calculate and plan warfarin dosing. It generates daily pill schedules from a weekly target and calculates the total pills needed for an appointment period. ![Language](https://img.shields.io/github/languages/top/Napatchouli/Vue-Quick-Warfarin-V2)
- [warfarin6](https://github.com/penpharmacy/warfarin6) - A straightforward web tool, likely for pharmacists, to verify a given daily regimen. It calculates the total weekly dose, compares it to a previous dose, and its main feature is to calculate the exact number of 2mg and 3mg pills to dispense based on the appointment duration. Built as a simple PWA for offline access. ![Language](https://img.shields.io/github/languages/top/penpharmacy/warfarin6)
- [warfarin-calculator](https://github.com/Paond55/warfarin-calculator) - A guideline-based web tool for clinicians to calculate warfarin dose adjustments based on INR and bleeding symptoms. It suggests new weekly doses and generates multiple daily pill regimens. Built as a Progressive Web App (PWA) for offline use. ![Language](https://img.shields.io/github/languages/top/Paond55/warfarin-calculator)
- [Warfarin-Dose-Calculator](https://github.com/prajwal-17/warfarin-dose-calculator) - A modern web application built with React and TypeScript for calculating oral anticoagulant dosages. It uniquely supports both **Warfarin** and **Acitrom**. For Warfarin, it provides distinct calculators for **initiation dosing** (a nomogram for the first 6 days) and **maintenance adjustments** based on target INR ranges. ![Language](https://img.shields.io/github/languages/top/prajwal-17/warfarin-dose-calculator)
- [Warfarin-Dosage-Calculator](https://github.com/pzweuj/warfarin-dosage-calculator) - A modern Next.js web application that implements multiple established pharmacogenomic algorithms (IWPC, Gage, Xiangya, Biss, Clover) for predicting initial warfarin dosage. Features a clean UI and multi-language support for comparison and educational purposes. ![Language](https://img.shields.io/github/languages/top/pzweuj/warfarin-dosage-calculator)
- [warfarin-planner](https://github.com/warfarin-net/warfarin-planner) - A sophisticated web tool for translating a target weekly warfarin dose into multiple, practical daily pill regimens. Features intelligent sorting to prioritize the simplest schedules (e.g., minimizing half-pills and pill types) and can calculate total pills needed for dispensing. Built as a PWA for offline use. ![Language](https://img.shields.io/github/languages/top/warfarin-net/warfarin-planner)

## Machine Learning & Research

*Projects focused on using machine learning, data analysis, and statistical modeling to predict optimal warfarin dosage.*

- [personalized-warfarin](https://github.com/cybergeist0/personalized-warfarin) - A complete machine learning project in a Jupyter Notebook that predicts personalized warfarin doses using both clinical and genetic data (VKORC1, CYP2C9) from the PharmGKB dataset. ![Language](https://img.shields.io/github/languages/top/cybergeist0/personalized-warfarin)
- [warfit-learn](https://github.com/gianlucatruda/warfit-learn) - A machine learning project using Python and scikit-learn to predict warfarin dosage. Includes a Jupyter Notebook for data exploration, model training, and evaluation. ![Language](https://img.shields.io/github/languages/top/gianlucatruda/warfit-learn)
- [warfarin-machinelearning](https://github.com/karneslab/warfarin-machinelearning) - A Python project comparing several machine learning models (e.g., Random Forest, SVR) to predict stable warfarin doses from clinical and pharmacogenomic data. ![Language](https://img.shields.io/github/languages/top/karneslab/warfarin-machinelearning)
- [Warfarin_Dose_Prediction](https://github.com/farahyusri12/warfarin_dose_prediction) - A well-documented project in a Google Colab notebook that builds a linear regression model to predict warfarin dose from the IWPC's clinical and genetic dataset. Includes detailed steps from data preprocessing to model evaluation and a final PDF report. ![Language](https://img.shields.io/github/languages/top/farahyusri12/warfarin_dose_prediction)
- [warfarin-dosing-ml-tool-](https://github.com/ifthekarhussain/warfarin-dosing-ml-tool-) - An end-to-end machine learning pipeline in a Jupyter Notebook for predicting warfarin dosage using the IWPC dataset. The project covers the full workflow from data preprocessing and feature engineering to training and comparing multiple models (including regression and classification). It culminates in an interactive prediction tool built with Gradio. ![Language](https://img.shields.io/github/languages/top/ifthekarhussain/warfarin-dosing-ml-tool-)

## Mobile Applications

*Open-source mobile apps for warfarin management.*

- [warfarin-management-app](https://github.com/amanjito/warfarin-management-app) - A comprehensive mobile app for patients to manage their warfarin therapy, featuring PT/INR tracking with charts, medication reminders via push notifications, and an AI-powered assistant. Built with React, TypeScript, and Supabase, and packaged for mobile using Capacitor. ![Language](https://img.shields.io/github/languages/top/amanjito/warfarin-management-app)

## Related Resources

*Links to relevant datasets, research papers, and articles.*

- [IWPC-Warfarin-Dataset](https://www.pharmgkb.org/page/iwpc) - The International Warfarin Pharmacogenetics Consortium (IWPC) dataset, widely used for building predictive models.
- [Gage et al., 2008](https://www.nejm.org/doi/full/10.1056/nejmoa0801363) - Seminal paper on using a pharmacogenetic algorithm to predict warfarin dose.

---

## Contributing

Contributions are always welcome! If you have a project you'd like to add, please read the [contribution guidelines](CONTRIBUTING.md) first, or simply open an [issue](https://github.com/pharmacist-sabot/awesome-warfarin/issues) or submit a [pull request](https://github.com/pharmacist-sabot/awesome-warfarin/pulls).

Please ensure your suggestion is open-source and directly relevant to the list.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, pharmacist-sabot has waived all copyright and related or neighboring rights to this work.
