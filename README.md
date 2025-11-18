Here’s a clean, ready-to-use **README.md** for your GitHub repo.

---

# Drone Flight Dataset and Lightweight LSTM-Based Wind Estimation for Semi-Autonomous Quadcopter Control

This repository contains code, resources, and documentation associated with the paper:

***“Drone Flight Dataset and Lightweight LSTM-Based Wind Estimation for Semi-Autonomous Quadcopter Control”***
(IEEE Access, 2025)

The project introduces a real-world drone flight dataset and a lightweight LSTM-based wind estimation model used to enhance semi-autonomous quadcopter control under wind disturbances.

---

## 📘 Overview

This repository includes:

* Scripts for preprocessing drone flight logs
* Training code for the lightweight LSTM wind estimator
* Model evaluation utilities
* Control interface demo logic (wind-compensated RC override)
* Documentation and experiment reproducibility notes

The dataset includes:

* Raw flight logs (10 missions × 2 control modes)
* Gyroscope, accelerometer, GPS, RC inputs, and estimator outputs
* Labeled wind vectors for supervised training

---

## 📂 Repository Structure

```
.
├── dataset_request/           # Instructions for requesting dataset access
├── models/                    # LSTM training and inference scripts
├── utils/                     # Preprocessing and evaluation utilities
├── examples/                  # Example inference & plotting
├── control_interface/         # Semi-autonomous RC override demonstration
└── README.md
```

---

## 📥 Dataset Access (Request Form)

The dataset is available **upon request** for research and academic use.

👉 **To access the dataset, please fill out this Google Form:**
**[Dataset Request Form]([YOUR_GOOGLE_FORM_LINK_HERE](https://forms.gle/7MFnHKf2oBPwHn356))**

### Requirements for Access:

1. Fill out the Google Form with your institutional details and intended use-case.
2. Agree to the dataset terms of use.
3. Agree to **cite the IEEE Access paper** when using the dataset in any publication.

---

## 📌 Citation

If you use the dataset, code, or models, please cite our paper:

```
@article{your_ieee_access_2025,
  title={Drone Flight Dataset and Lightweight LSTM-Based Wind Estimation for Semi-Autonomous Quadcopter Control},
  author={Ruppikha Sree Shankar and Vatsal Siotia and Rani Oomman Panicker}
  journal={IEEE Access},
  year={2025},
  doi={XXXXXX}
}
``

## 📫 Contact

For questions, collaborations, or research use-cases, feel free to reach out via the contact details provided in the Google Form.

