# Insurance Customer Analysis Project

## Overview

Sure Tomorrow Insurance Company aims to leverage machine learning to address several key business objectives. This project evaluates the feasibility of using machine learning to:

* **Task 1:** Identify customers similar to a given customer for targeted marketing efforts.
* **Task 2:** Predict whether a new customer is likely to receive an insurance benefit, comparing trained models to a dummy baseline.
* **Task 3:** Forecast the number of insurance benefits a new customer will likely receive using a linear regression model.
* **Task 4:** Protect customer personal data while preserving the model's performance from Task 3 through data masking or obfuscation.


## Dataset Description

The dataset is stored in `datasets/insurance_us.csv`. It contains the following features:

* **Features:**
    * `gender`: Gender of the insured person.
    * `age`: Age of the insured person.
    * `salary`: Salary of the insured person.
    * `family_members`: Number of family members of the insured person.
* **Target:**
    * `insurance_benefits`: Number of insurance benefits received by the insured person in the last five years.

## Project Structure
