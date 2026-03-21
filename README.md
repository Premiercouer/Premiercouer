# Hi, I'm Jianzhuo Zhang 👋

I'm a Data Science & AI graduate student with hands-on experience building
production-scale ML systems on GCP. I enjoy problems that sit at the
intersection of data engineering, machine learning, and analytical thinking —
especially when the data is messy, the rules are undocumented, and the scale
is large.

---

## 🔧 Featured Projects

### [Health Recommendation ML System](https://github.com/Premiercouer/health-recommendation-ml-system)
Reverse-engineered a proprietary health recommendation engine at production scale —
without access to its source code — by building a four-stage pipeline on GCP.

- Processed **429M rows (331 GB)** entirely in BigQuery SQL
- Developed a **frequency-variance framework** to attribute 33 recommendation
  tips to their controlling health dimensions from output text alone
- Identified that the engine's internal random sampling made direct tip
  prediction unlearnable; redesigned labels using ABCD rule classification,
  delivering a **+68% improvement in model precision**
- Trained **18 BigQuery ML models** processing ~22 TB in ~12.5 hours
- Deployed an **end-to-end inference pipeline** (`predict.py`) from raw JSON
  input to natural language health advice output

### [Health Recommendation Engine Analysis](https://github.com/Premiercouer/health-recommendation-engine-analysis)
Phase 1 of the above: exploratory analysis on a 746k-row sample that established
the rule discovery methodology later scaled to 429M rows.

- Identified the dataset as a **deterministic combinatorial lookup table**,
  not sampled data — a foundational insight that shaped the entire approach
- Built a **regex end-anchor + graph merge pipeline** (NetworkX) to parse
  concatenated recommendation text with internal punctuation
- Introduced the **ABCD classification framework** for rule-engine tip behaviour
- Compared XGBoost, Random Forest, and Logistic Regression for multi-label
  recommendation prediction (best F1: 0.7681)

---

## 🛠️ Skills

**Languages:** Python · SQL

**ML & Data:** scikit-learn · XGBoost · pandas · NumPy · SciPy · NetworkX

**Cloud & Data Engineering:** BigQuery · BigQuery ML · Google Cloud Storage ·
Vertex AI Workbench · GCP Dataproc · AWS (S3 · SageMaker · Athena)

**Visualization:** Matplotlib · Seaborn · Power BI

**Tools:** Jupyter · Git

---

## 📫 Reach me

[GitHub](https://github.com/Premiercouer) · jianzhuozhang643@gmail.com
