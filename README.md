# CCDATSCL Midterm Exam - COM221

Midterm examination for COM221 (Computer Concepts and Data Science) at CCDATSCL. This exam analyzes hotel booking demand data to demonstrate competency in data science concepts, statistical analysis, and data visualization techniques.

## Table of Contents

- [About](#about)
- [Exam Structure](#exam-structure)
- [Dataset](#dataset)
- [Exam Questions](#exam-questions)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [File Structure](#file-structure)
- [Grading Rubric](#grading-rubric)
- [Acknowledgments](#acknowledgments)

## About

This repository contains the midterm examination work for **COM221 - Computer Concepts and Data Science** at CCDATSCL. The exam focuses on applying data science techniques to real-world hotel booking data, demonstrating proficiency in:

- Data manipulation and cleaning using pandas
- Statistical analysis and distribution assessment
- Data visualization with matplotlib and plotly
- Pattern recognition and interpretation
- Drawing data-driven conclusions

**Note**: This is exam material, not a production project.

## Exam Structure

The exam consists of 5 questions, each worth 20 points (100 points total). Each question is evaluated based on:

- **Correct Analysis & Computation** (8 points) - Proper use of pandas operations, accurate statistics
- **Appropriate Use of Visuals/Tables** (6 points) - Relevant visualizations, appropriate plot types, clear labels
- **Interpretation and Reasoning** (6 points) - Clear conclusions, data-supported interpretations, logical reasoning

## Dataset

The project uses the **Hotel Booking Demand** dataset from Kaggle, which contains booking information for both resort and city hotels.

### Dataset Overview

- **Source**: Kaggle - Hotel Booking Demand by Jesse Mostipak
- **Format**: CSV file (`hotel_bookings.csv`)
- **Records**: Contains booking data with multiple attributes

### Key Variables

- **hotel**: Hotel type (H1 = Resort Hotel, H2 = City Hotel)
- **is_canceled**: Cancellation status (1 = canceled, 0 = not canceled)
- **lead_time**: Days between booking and arrival date
- **arrival_date_year/month/week_number/day_of_month**: Arrival date information
- **stays_in_weekend_nights/stays_in_week_nights**: Number of nights stayed
- **adults/children/babies**: Number of guests
- **meal**: Meal package type (BB, HB, FB, SC)
- **country**: Country of origin (ISO 3155-3:2013 format)
- **market_segment**: Market segment designation
- **distribution_channel**: Booking distribution channel
- **is_repeated_guest**: Repeated guest indicator
- **previous_cancellations**: Previous cancellations by customer
- **reserved_room_type/assigned_room_type**: Room type codes
- **booking_changes**: Number of amendments made
- **deposit_type**: Deposit status (No Deposit, Non Refund, Refundable)
- **days_in_waiting_list**: Days in waiting list
- **customer_type**: Booking type (Contract, Group, Transient, Transient-party)
- **adr**: Average Daily Rate
- **required_car_parking_spaces**: Parking spaces required
- **total_of_special_requests**: Number of special requests
- **reservation_status**: Last reservation status
- **reservation_status_date**: Date of last status update

## Exam Questions

The midterm exam addresses five analytical questions, each worth 20 points:

### Question 1: Dataset Overview and Core Distributions (20 points)

**Question**: What do the shapes and spread of the `lead_time` and `adr` distributions suggest about typical booking behavior and extreme cases?

**Requirements**:
- Analyze the distribution of lead_time and adr
- Use appropriate summary statistics and visualizations
- Identify any skewness and/or outliers

### Question 2: Booking Cancellations and Lead Time (20 points)

**Question**: Do bookings with longer lead times tend to cancel more often?

**Requirements**:
- Compute appropriate summary statistics
- Use at least one visualization
- Clearly describe the pattern observed

### Question 3: Seasonality and Pricing (20 points)

**Question**: Do Resort Hotels and City Hotels exhibit different seasonal pricing behaviors throughout the year? If so, during which months are these differences most pronounced?

**Requirements**:
- Aggregate ADR by month and hotel type
- Use a visualization to support analysis
- Identify at least one seasonal pricing pattern

### Question 4: Customer Behavior (20 points)

**Question**: Analysis of customer patterns and preferences in hotel bookings.

### Question 5: Booking Cancellation Insights (20 points)

**Question**: Deep dive into factors influencing booking cancellations.

## Requirements

- Python 3.7 or higher
- pandas
- matplotlib
- plotly
- kagglehub (for dataset download)
- numpy
- jupyter notebook

## Setup Instructions

To run the exam notebook:

1. Clone this repository:

```bash
git clone https://github.com/rbodarve/CCDATSCL_EXAM_COM221.git
cd CCDATSCL_EXAM_COM221
```

2. Install required packages:

```bash
pip install pandas matplotlib plotly kagglehub numpy jupyter
```

3. Download the dataset:

The notebook includes code to automatically download the dataset using kagglehub. The dataset (`hotel_bookings.csv`) will be downloaded to the working directory when running the notebook cells.

4. Launch Jupyter Notebook:

```bash
jupyter notebook CCDATSCL_EXAM.ipynb
```

5. Execute the cells sequentially to view the exam responses and analysis.

## File Structure

```
CCDATSCL_EXAM_COM221/
├── CCDATSCL_EXAM.ipynb    # Midterm exam notebook with questions and answers
├── hotel_bookings.csv     # Dataset file (downloaded via notebook)
└── README.md              # This file
```

## Grading Rubric

Each of the 5 questions is worth 20 points and graded based on:

### Correct Analysis & Computation (8 points)
- Correct use of pandas operations (groupby, aggregation, filtering)
- Accurate statistics or summaries

### Appropriate Use of Visuals/Tables (6 points)
- Visualization or table is relevant to the question
- Plot type is appropriate (bar, boxplot, line, etc.)
- Labels and axes are clear

### Interpretation and Reasoning (6 points)
- Conclusions are clearly stated
- Interpretations are supported by data
- Reasoning is logical and coherent

**Total**: 100 points

## Acknowledgments

- **Dataset Source**: Hotel Booking Demand dataset by Jesse Mostipak on Kaggle
- **Course**: COM221 - Computer Concepts and Data Science
- **Institution**: CCDATSCL
- **Exam Type**: Midterm Examination
- **README Template**: Inspired by the [Awesome README](https://github.com/matiassingers/awesome-readme) collection by [Matias Singers](https://github.com/matiassingers)

---

*This is academic exam material for educational purposes only.*