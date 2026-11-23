# Timeseries and forecasting

A collection of related Python data analysis and research projects built with Jupyter Notebooks.

## 📂 Projects

| Project | Description | Key Libraries |
| :--- | :--- | :--- |
| **[Project Alpha](./project-alpha/)** | Brief one-sentence summary of what this notebook/project explores. | `pandas`, `matplotlib` |
| **[Project Beta](./project-beta/)** | Brief one-sentence summary of what this notebook/project explores. | `scikit-learn`, `seaborn` |
| **[Shared Utilities](./shared/)** | Reusable helper functions and data loaders used across notebooks. | — |

---

## 🛠️ Setup & Installation

This repository uses **[uv](https://astral.sh)** to manage a single unified Python environment across all projects.

### 1. Install Dependencies
Clone the repository and sync the environment from the root directory:

```bash
git clone https://github.com[your-username]/[repo-name].git
cd [repo-name]
uv sync --all-groups
```

### 2. Run Notebooks
* **VS Code / Cursor:** Open any `.ipynb` file, click **Select Kernel** in the top right, and choose the `.venv` environment located at the root of this repo.
* **JupyterLab (Browser):** Launch Jupyter directly through `uv`:
  ```bash
  uv run jupyter lab
  ```

---

## 📝 Conventions
* **Dependencies:** Managed centrally in `pyproject.toml`. Project-specific packages are organized under `[dependency-groups]`.
* **Commits:** Prefixed with the target folder (e.g., `project-alpha: add exploratory analysis`).
