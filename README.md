# Enhanced Anti-Money Laundering (AML) System

## Abstract
This project addresses the growing issue of money laundering, which is a global financial threat, with an estimated $1.6 trillion laundered annually. Traditional Anti-Money Laundering (AML) methods often struggle to adapt to modern techniques, highlighting the need for more advanced detection systems. This research presents a comprehensive solution utilizing data mining and machine learning to enhance the efficiency of AML systems.

## System Components
The proposed system consists of four primary components:

1. **Data Cleaning**: Ensures high-quality financial transaction data by removing inconsistencies and inaccuracies.
2. **Mined Frequent Rules**: Identifies transaction patterns and anomalies through rule-mining techniques such as FP-growth.
3. **Classifier Construction**: Builds machine learning models (e.g., Random Forest and XGBoost) to detect suspicious transactions.
4. **Reporting**: Provides dashboards and analytics tools to generate alerts and ensure compliance with financial regulations.

## Objective
The objective of this project is to develop a robust and adaptable system capable of:
- Detecting suspicious transactions with improved accuracy.
- Enhancing real-time monitoring capabilities.
- Facilitating compliance with global financial regulations.

## Approach
Through a detailed review of current AML systems and their limitations, the project demonstrates how the integration of:
- **Data mining techniques**
- **Machine learning algorithms**
- **Visualization tools**

Can substantially improve the detection of money laundering activities. The system has been tested under realistic conditions and has shown promising results in enhancing detection accuracy, usability, and scalability.

## Contributions
This project contributes to the growing field of AML research by providing a solution that leverages advanced technologies to address modern challenges in financial crime detection. It is a practical tool that can benefit:
- Financial institutions
- Regulatory bodies
- Law enforcement agencies

In combating money laundering more effectively.

## Results
The system has demonstrated:
- **Enhanced detection accuracy** for identifying suspicious transactions.
- **Improved usability** with intuitive dashboards and reporting tools.
- **Scalability** for handling large volumes of financial transaction data.

## Installation
To get started with the project, follow these steps:

1. Clone this repository.
2. Install the required dependencies using the following command:
   ```bash
   pip install -r requirements.txt

# Project Folder Structure

This is the folder structure for the **Enhance_Anti_Money_Laundering** project:
```
Enhance_Anti_Money_Laundering
├── .vscode
├── catboost_info
│   └── learn
├── data
├── data_processed
├── logs
├── predictions
├── reports
├── saved_models
├── src
├── static
│   ├── css
│   ├── fonts
│   │   └── Inter
│   │       └── static
│   ├── images
│   │   └── logo
│   ├── js
│   └── lib
│       ├── apexcharts
│       ├── bootstrap_5
│       ├── DataTables
│       ├── fontawesome
│       │   ├── css
│       │   ├── js
│       │   ├── less
│       │   ├── metadata
│       │   ├── scss
│       │   ├── sprites
│       │   ├── svgs
│       │   │   ├── brands
│       │   │   ├── regular
│       │   │   └── solid
│       │   └── webfonts
│       ├── fullcalender
│       ├── jQuery
│       ├── jvectormap
│       └── slick-1.8.1
│           └── fonts
└── templates
```

### How to use this structure:
- **.vscode**: Configuration files for Visual Studio Code.
- **catboost_info**: Contains learning information related to CatBoost.
- **data**: Raw data for the project.
- **data_processed**: Processed data for the project.
- **logs**: Log files generated during execution.
- **predictions**: Predictions output generated by the model.
- **reports**: Project reports or outputs.
- **saved_models**: Stored models.
- **src**: Source code for the project.
- **static**: Static files like CSS, fonts, images, and JavaScript libraries.
- **templates**: HTML templates or other related files.

---

This structure represents the organization of the project to help you navigate through different directories and files.

