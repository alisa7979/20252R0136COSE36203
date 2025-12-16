### 1. `ML_Termproj.ipynb` (Final Version)
- **Purpose:** The final project report code.
- **Content:** A consolidated version including Data Loading, EDA, Decision Tree modeling, and K-means++ clustering.
- **Features:** Contains the final cluster metrics (average budget, revenue, ROI per cluster) and the finalized project structure. This is the main file for submission.

### 2. `movie_analysis.ipynb` (Base Analysis)
- **Purpose:** The main working file containing the full analysis cycle.
- **Content:** Includes detailed conclusions (Section 8) regarding prediction results (70-80% accuracy) and movie segmentation.
- **Features:** Provides detailed descriptions of important features and justification for the selected number of clusters (3-5).

### 3. `movie_analysis_v1.ipynb` (Focus on Data Leakage)
- **Purpose:** An experimental version with a strict definition of the target variable.
- **Target Definition (V1):** `is_hit = (revenue >= 2 * budget)`.
- **Features:** - Strict control over **Data Leakage**: excludes features unavailable during the production phase (e.g., `vote_average`).
  - Explores strategies for model improvement (ensembles, cluster-specific models).

### 4. `movie_analysis_v2.ipynb` (Business Insights)
- **Purpose:** A version focused on extracting business insights from the data.
- **Features:**
  - Detailed analysis of Hit Rate by category.
  - **Insights:** Top genres by profitability (Horror, Music), seasonality effects (Winter vs. Spring), and budget tier analysis (Low vs. Blockbuster).
