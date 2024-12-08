# Buffer Extent Analysis Repository

This repository contains data and results for analyzing the ROC, AUC and the optimal buffer extents across various layers. The data is organized into three main folders: `Individual Layers`, `Intersection`, and `Union`.

---

## Repository Structure

### 1. **`individual Layers` Folder**
   - This folder contains data and results for analyzing individual layers.
   - **CSV File Types**:
     1. **Individual_optimal_buffer_extent.csv**:
        - These files provide the calculated optimal buffer extent for every layer.
     2. **ROC Analysis Files**:
        - These files contain the following columns:
          - **Threshold**: every 2 km buffer distance where the ROC is calculated.
          - **TPR (True Positive Rate)**
          - **FPR (False Positive Rate)**
          - **AUC** the AUC value
          - **difference**: The difference between TPR and FPR values for each threshold.

---

### 2. **`intersection` Folder**
   - Contains data and results for layers that intersect with one another.
   - **CSV File Types**:
     1. **Intersect_optimal_buffer_extent.csv**:
        - These files provide the min and max optimal buffer extent for each intersection layer.
     2. **ROC Analysis Files**:
        - These files contain the following columns:
          - **Threshold**: every 2 km buffer distance where the ROC is calculated.
          - **TPR (True Positive Rate)**
          - **FPR (False Positive Rate)**
          - **AUC** the AUC value
          - **difference**: The difference between TPR and FPR values for each threshold.

---

### 3. **`union` Folder**
   - Contains data and results for combined layers (union of layers).
   - **CSV File Types**:
     1. **Union_optimal_buffer_extent.csv**:
        - These files provide the min and max optimal buffer extent for each union layer.
     2. **ROC Analysis Files**:
        - These files contain the following columns:
          - **Threshold**: every 2 km buffer distance where the ROC is calculated.
          - **TPR (True Positive Rate)**
          - **FPR (False Positive Rate)**
          - **AUC** the AUC value
          - **difference**: The difference between TPR and FPR values for each threshold.


---

## Contact
For questions or further assistance, feel free to reach out at [azim.binrossalim@research.uwa.edu.au].
