# Mouse Sleep Stage Plotter (MATLAB App)

A powerful and user-friendly MATLAB tool for analyzing and visualizing mouse sleep EEG/EMG data. This app provides comprehensive visualization, intelligent data selection, artifact removal, and group-level analysis designed for sleep stage research.

---

## 🧠 Features

- Import and analyze **EEG/EMG signals**
- Intelligent **artifact detection and removal**
- Support for custom **sleep stage annotations (TSV format)**
- Generate **Zeitgeber Time-aligned** hypnograms and state maps
- Fully customizable **time-frequency plots**, including:
  - Global overview
  - Single-subject detail
  - Group-wise comparison
- Built-in **statistical analysis** (e.g., t-tests, hourly summaries)
- Export plots optimized for **two-column journal formats**
- Supports **gigabyte-scale** EEG data via memory-efficient processing
- Designed for **users with or without MATLAB** installed

---

## 🚀 Installation

### Option 1: With MATLAB Installed

1. Download `mice_sleep_analysis.mlappinstall`
2. Open MATLAB → Go to **"APPS" tab** → Click **"Install App"**
3. Browse to select the `.mlappinstall` file
4. App will appear in MATLAB App list

### Option 2: Without MATLAB (Standalone)

1. Download the **installer package** from [Releases](https://github.com/yourusername/MouseSleepStagePlotter_matlab_CN/releases/tag/v1.0.0)
2. Run the installer (no need for MATLAB license)

---

## 📦 Folder Structure

MouseSleepStagePlotter_matlab_CN/ │ ├── mice_sleep_analysis.mlappinstall # MATLAB App file ├── for_redistribution_files_only/ # Files for standalone version ├── for_testing/ # Sample EEG/EMG data & annotations ├── example_data.tsv # Example TSV annotation ├── doc/ │ └── manual_CN.pdf # 中文用户手册 ├── README.md # This file ├── .gitignore


---

## 🛠️ How to Use

1. Launch the app
2. Choose your analysis method (based on your computer performance)
3. Select the EEG/EMG data folder
4. Choose desired visualization mode:
   - Hypnogram plotting
   - Time-frequency heatmap
   - Sleep state statistics
5. Customize plotting parameters:
   - Time range
   - ZT alignment
   - Filtering and color scale

📌 Tips:
- You can **re-select time range** if needed
- Default values are provided for all settings
- Handles **irregular signal lengths** and non-standard stages

---

## 📊 Output Examples

- Sleep stage hypnogram (24h aligned)
- Per-hour sleep state distribution
- Artifact-removed time-frequency plots
- Group comparison of REM/NREM dynamics

All images are automatically named, resized, and formatted for publication.

---

## 📈 Requirements

- MATLAB R2021a or later (for `.mlappinstall` version)
- Windows OS for standalone version
- Minimum 8GB RAM, GPU recommended for high-resolution plots

---

## 🧑‍💻 Author

**黄勇志 / Yongzhi Huang**  
📧 yhuang849@connect.hkust-gz.edu.cn  
The Hong Kong University of Science and Technology (Guangzhou)

---

## 📝 License

This project is for academic use. For other usage or licensing, please contact the author.

---

## 🌐 Language Support

- Interface language: 中文
- Documentation: 中文 + English (coming soon)

---

## 🙌 Acknowledgments

Special thanks to the users who provided feedback and test data during development.
