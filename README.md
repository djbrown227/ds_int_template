Here’s your updated `README.md`, with simplified **folder purpose descriptions** instead of showing the full directory tree:

---

# 🧪 Data Science Project Template

A lightweight, modular template for structuring data science projects and publishing results using **GitHub Pages + Jekyll**. Ideal for showcasing analysis, models, and visualizations in a clear and reproducible way.

---

## 🚀 Features

* **Jupyter notebooks** organized by step: fetch, clean, model, visualize
* **Raw vs processed data** separation for reproducibility
* **Modular scripts** to automate common tasks
* **Built-in publishing** with GitHub Pages and Jekyll
* **Requirements file** for easy environment setup

---

## 🗂️ Folder Structure & Purpose

* `data/`: Store all datasets

  * `raw/`: Original, unedited datasets
  * `processed/`: Cleaned or transformed data for analysis

* `docs/`: Public-facing project site built with Jekyll (auto-served by GitHub Pages)

  * Includes homepage (`index.md`), config file (`_config.yml`), and static assets (images, styles, JS)

* `images/`: Extra visuals used in notebooks or reports

* `notebooks/`: Step-by-step Jupyter notebooks

  * Fetch data → Clean & EDA → Modeling → Visualization

* `scripts/`: Reusable Python code

  * Data fetching and cleaning logic separated from notebooks

* `requirements.txt`: List of Python dependencies for setting up the environment

* `README.md`: Overview of the project, structure, and instructions

---

## 🛠️ How to Use

1. **Clone this repo** and set up your environment

   ```bash
   git clone https://github.com/your-username/your-repo.git  
   cd your-repo  
   pip install -r requirements.txt  
   ```

2. **Run notebooks** in order (`notebooks/`)

   * Use provided `scripts/` to avoid redundant code

3. **Add your analysis and visuals**

   * Save images or charts in `images/` or `docs/assets/images/` if publishing

4. **Customize the site**

   * Edit `docs/index.md` and `_config.yml`
   * Push to `main` branch and enable GitHub Pages via repo settings

---

## 🌐 GitHub Pages Publishing

* GitHub will automatically build your site from the `docs/` folder.
* Make sure Jekyll is enabled and `docs/_config.yml` has basic settings like title and theme.
* Customize your site homepage via `docs/index.md`.

---

## 📦 Requirements

Install all Python dependencies with:

```bash
pip install -r requirements.txt
```

---