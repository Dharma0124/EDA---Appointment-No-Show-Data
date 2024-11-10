# Exploratory Data Analysis (EDA) for Appointment No-Show Data

## Project Overview
This project explores factors influencing patient no-shows for medical appointments. Using various Python libraries, this analysis investigates potential relationships between patient characteristics and appointment attendance rates.

## Dataset
- **Source**: Kaggle (Dataset includes anonymized patient information and appointment details)
- **Features**:
  - `PatientId`: Unique identifier for each patient.
  - `AppointmentID`: Unique identifier for each appointment.
  - `Gender`: Patient's gender.
  - `ScheduledDay`: Date and time when the appointment was scheduled.
  - `AppointmentDay`: Date of the appointment.
  - `Age`: Patient's age.
  - `Neighbourhood`: Location of the appointment.
  - `Scholarship`: Whether the patient is enrolled in welfare programs.
  - `Hypertension`, `Diabetes`, `Alcoholism`, `Handcap`: Health indicators.
  - `SMS_received`: Whether a reminder SMS was received.
  - `No-show`: Whether the patient missed the appointment.

## Steps in the Analysis
1. **Import Libraries**: Loaded essential libraries like Pandas, NumPy, Matplotlib, and Seaborn for data handling and visualization.
2. **Data Loading**: Imported the dataset and conducted initial inspections to understand its structure.
3. **Data Cleaning**:
   - Checked for and handled missing values.
   - Converted columns to appropriate data types.
4. **Feature Engineering**: 
   - Extracted features such as `AppointmentWeekday` and `ScheduledWeekday`.
5. **Exploratory Data Analysis (EDA)**:
   - Conducted univariate and bivariate analyses.
   - Visualized distribution of ages, no-show rates, and other factors.
6. **Correlation Analysis**:
   - Calculated and visualized correlations among numerical features using a heatmap.
7. **Handling Missing Data**: Imputed missing values where needed.

## Key Insights
- **Age**: Younger patients tended to have higher no-show rates.
- **SMS Reminders**: Patients who received SMS reminders had slightly lower no-show rates.
- **Day of the Week**: Appointments scheduled later in the week showed different attendance patterns.

## Dependencies
- Python 3.7 or higher
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-link>
