# Foundational Data Science & Preprocessing Portfolio

Welcome to my fundamental data analytics portfolio repository. This repository aggregates a collection of programmatic analysis scripts and processed outputs demonstrating technical capabilities in high-performance array manipulation, automated exploratory analytics, and rigorous data sanitization workflows.

---

## 📂 Repository Contents & Structure

### 📊 Project 1: NumPy Data Explorer
* **Core Framework:** `NumPy`
* **Key Tasks Addressed:** High-dimensional array initialization, custom multidimensional matrix slicing, element-wise mathematical vectorization, and structural broadcasting.
* **Performance Discovery:** Bypassed native iterative list overheads using contiguous memory allocation blocks, yielding operation speedups exceeding **40x** compared to standard Python loops.
* **Deliverable:** `Project_1_NumPy_Data_Explorer.pdf`

### 📈 Project 2: Pandas CSV Reader & Basic Analysis
* **Core Framework:** `Pandas`
* **Key Tasks Addressed:** Relational database object ingestion (`read_csv`), matrix shape sampling (`.head()`, `.tail()`), descriptive central-spread profiling configurations (`.describe()`), and complex multi-conditional column subset slicing.
* **Deliverable:** `Project_2_Pandas_Data_Explorer.pdf`

### 🧹 Project 3: Data Preprocessing & Integrity Framework
* **Core Framework:** `Pandas` & `NumPy`
* **Key Tasks Addressed:** Alphanumeric variable type alignment, dynamic evaluation data coercion (`pd.to_numeric`), duplicate record filtering, text-border white-space trimming, and central tendency statistics imputation.
* **Technical Implementation Detail:** Handles mixed-type noise entries (e.g., `'Unknown'`) safely into `NaN` elements, applying localized median tracking metrics to stabilize distributions without outlier bias.
* **Deliverable:** `Project_3_Data_Cleaning.pdf`

---

## 🛠️ Environmental Setup & Local Execution
To execute or interact with any underlying code fragments highlighted within the project documentation, set up your localized environment using the following packages:

```bash
# Clone the portfolio repository locally
git clone [https://github.com/YOUR_USERNAME/Data-Analytics-Basics-Portfolio.git](https://github.com/zubiyaAnsari/Data-Analytics-Basics-Portfolio.git)

# Install core analysis dependencies
pip install numpy pandas
