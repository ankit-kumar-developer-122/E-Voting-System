# E-Voting System 🗳️

A secure and efficient electronic voting system built with Python.  
This project leverages computer vision and machine learning to authenticate voters and record votes digitally.

---

## 📌 Features
- **Face Recognition Authentication** using OpenCV.
- **Secure Voting Process** with data stored in CSV format.
- **Cross-platform Compatibility** (Windows support via pywin32).
- **Scalable Design** for future integration with blockchain or cloud services.

---

## Project Structure

├── add_faces.py        # Script to register voter faces
├── give_vote.py        # Script to cast votes after authentication
├── Votes.csv           # Stores voting data
├── background.png      # UI background image
├── README.md           # Project documentation


## 🛠️ Requirements
Install the following dependencies before running the project:

- `opencv-python`
- `scikit-learn`
- `pywin32`

You can install them with:
```bash
pip install opencv-python scikit-learn pywin32


