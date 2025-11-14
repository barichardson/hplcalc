# Placeholder repo for [hplcalc](https://hplcalc.net) webapp.

Use this to submit issues and suggest features.

Built on Go using net/http and http/template libraries designed to run as a standalone container.
Sources will be shared in the future after additional code review.

## Features:

#### Generate HPL.dat based of pre-defined templates for common use cases.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/bf6ecc00-716f-4668-9fa3-0c50720274ac" />

---
#### Generated HPL.dat file includes full configuration URL to easily see all inputs used during generation and allow easy modifications.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/661f7df2-3fa2-4484-9c65-3e2ed5c7852a" />

---
#### Calculate Rpeak and actual efficiency based on hardware configuration information provided.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/844881a5-bcad-4310-ae54-2ece9aeafb26" />

---
#### Provides guidance if input values are likely to result in a non-optimal run.

Example: If PxQ grid calculation is too far off-square. (Greater than a 2.5 aspect ratio.)

<img width="600" alt="image" src="https://github.com/user-attachments/assets/29da5f80-4b63-4b7d-933f-8a5d06122686" />

Example: If NB value input is less than recommended when using NVIDIA GPU template.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/4fadcdcd-98bb-48fe-8c60-e310be76ddfd" />

---

#### Machinefile creation.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/57053bee-ae18-46f5-a0fd-dc7d2e9606d4" />

---

#### Linear Rankfile creation.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/a14c31d5-fc1b-41d1-97f7-f9762f895839" />
