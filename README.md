# LIGO Strain Visualizer

This project demonstrates how to extract, filter, and visualize gravitational wave data from the LIGO experiment using HDF5 files. It is built using Python and includes signal processing techniques suitable for Data Engineering and Scientific Computing portfolios.

## 🔭 Project Overview

- Load real-world LIGO data stored in HDF5 format
- Visualize raw strain signal
- Apply a bandpass filter (20–300 Hz)
- Display the frequency content using FFT

## 📁 Project Structure

```
ligo-strain-visualizer/
├── data/                   # Contains the LIGO_data.hdf5 file (not included)
├── notebooks/              # Jupyter notebooks for analysis and visualization
├── scripts/                # Python scripts for modular code (optional)
├── requirements.txt        # Dependencies for running the project
└── README.md               # Project overview and usage instructions
```

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/ligo-strain-visualizer.git
cd ligo-strain-visualizer
```

### 2. Install dependencies

We recommend using a virtual environment:

```bash
pip install -r requirements.txt
```

### 3. Place the data file

Download `LIGO_data.hdf5` from the [GWOSC tutorials](https://www.gw-openscience.org/tutorials/) or use the copy provided here in data/.

Place it in the `data/` folder.

### 4. Run the notebook

Open the notebook in `notebooks/` using Jupyter or VSCode and follow along.

```bash
jupyter notebook notebooks/01_visualize_strain.ipynb
```

## ✨ Future Enhancements

- Add spectrogram visualizations
- Stream data into a pipeline using Apache Kafka / Spark
- Build a dashboard in Streamlit

---

Crafted with cosmic curiosity by Aleksandar Manolov 🚀✨
