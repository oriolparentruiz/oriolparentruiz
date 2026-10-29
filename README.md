# Hi, I'm Oriol 👋

Data Science and Engineering student at **UPC (Barcelona)**. I work on data engineering, machine learning, statistics and optimization, mostly through university projects done in teams. Below is a selection, each one with its own repository and a full write-up.

**Stack:** Python · R · C++ · SQL · Spark · MPI/OpenMP · Airflow · MLflow · scikit-learn · TensorFlow · MongoDB · Delta Lake · AWS

---

## 📂 Projects

### Data engineering & ML

#### 🏙️ [Barcelona Housing & Urban Resilience](https://github.com/oriolparentruiz/barcelona_housing__urban_resilience)
End-to-end Data Engineering and MLOps pipeline that analyses Barcelona housing prices against urban indicators (immigration, unemployment, income). Raw JSON/CSV is ingested into Parquet, cleaned with Spark and upserted into MongoDB, aggregated into a Delta Lake table, and used to train Spark ML models tracked in MLflow. Everything is orchestrated with an Airflow DAG and is fully reproducible from a single setup script.
`Airflow` `Spark` `MongoDB` `Delta Lake` `MLflow` `Python`

#### ⚡ [Spark IMDb Analytics](https://github.com/oriolparentruiz/Spark_IMDb_Analytics)
Performance comparison of the same actor–director collaboration analysis implemented in sequential Python, Spark RDD and Spark DataFrame, run on a 4-node Apache Spark cluster on AWS EC2 with datasets of up to ~20 million IMDb rows. Sequential Python wins on small inputs, the break-even point is around 3× the original data, and at 9× Spark DataFrame is about 47% faster than Python and 53% faster than RDD.
`Spark` `PySpark` `AWS EC2` `Python` `Benchmarking`

#### 🩺 [Liver Patient Classification Using ML Methods](https://github.com/oriolparentruiz/liver_patient_classification_using_ml_methods)
Kaggle InClass competition on the Indian Liver Patient Dataset (ILPD). Covers the full ML cycle on an imbalanced dataset: preprocessing inside scikit-learn pipelines, 12 model families compared with repeated stratified cross-validation, class-imbalance handling, voting and stacking ensembles. A tuned **Extra Trees** model won out (CV F1 macro ≈ 0.68), and no ensemble beat it.
`Python` `scikit-learn` `imbalanced-learn` `Jupyter`

### Statistics & forecasting

#### 🚗 [Forecasting Monthly Car Manufacturing in Spain](https://github.com/oriolparentruiz/forecasting_monthly_car_manufacturing_in_spain)
Box-Jenkins (ARIMA/SARIMA) analysis of monthly passenger car production in Spain since 1994: identification, estimation, residual diagnostics, out-of-sample validation and 12-month forecasts. Extended with calendar-effect regressors (trading days, Easter) and automatic outlier treatment, which gave the largest improvement in fit.
`R` `R Markdown` `Time series`

#### 📊 [Multivariate Data Analysis of Spotify Tracks](https://github.com/oriolparentruiz/multivariate_data_analysis_project)
PCA, MDS (Euclidean, Gower, non-metric), MCA, hierarchical clustering and LDA/QDA applied to 1,686 high-popularity Spotify tracks to relate audio features to genre. QDA reaches ≈ 70% genre accuracy, and genres line up along three axes: sonic intensity, rhythmic accessibility and lyrical focus.
`R` `FactoMineR` `Clustering` `Discriminant analysis`

### Algorithms, optimization & HPC

#### 🧵 [Textile Optimization](https://github.com/oriolparentruiz/texitle_optimization)
Three C++ solvers for a 2D strip-packing problem (minimising the length of a fixed-width fabric roll): exhaustive search with pruning, a greedy heuristic and simulated annealing. Tested on small, medium and large instances.
`C++` `Backtracking` `Greedy` `Simulated annealing`

#### 🖥️ [HPC Benchmarking Project](https://github.com/oriolparentruiz/HPC_Benchmarking_Project)
Benchmarking of performance, scalability and energy efficiency on a supercomputing cluster (up to 8 nodes, 896 cores). Compares MPI, OpenMP and hybrid MPI+OpenMP configurations on the NAS Parallel Benchmarks (BT-MZ, LU-MZ, SP-MZ), measured with EAR energy monitoring, plus TensorFlow GPU workloads with basic vs mixed precision. A hybrid configuration with 8 threads per process was fastest and most energy efficient (BT-MZ on 8 nodes: 3.3× faster than MPI-only), and mixed precision cut GPU energy use.
`MPI` `OpenMP` `SLURM` `EAR` `TensorFlow` `Python`

#### 🗺️ [Geographic Route Mapping and Medieval Monuments Routing](https://github.com/oriolparentruiz/geographic_route_mapping_and_medieval_monuments_routing)
Interactive tool that downloads hiking GPS segments from OpenStreetMap for a user-defined region, infers a simplified graph with K-Means clustering, and computes shortest routes to nearby medieval monuments. Results are exported as 2D maps (PNG) and 3D views (KML for Google Earth).
`Python` `NetworkX` `scikit-learn` `OpenStreetMap` `KML`

### Ethics & engineering

#### ⚖️ [The AI Minister: Ethical and Engineering Implications of Automating the Ministry of Territory and Housing](https://github.com/oriolparentruiz/ethical_and_engineering_implications_of_automating_the_ministry_of_territory_and_housing)
Academic study of a hypothetical AI system managing a public ministry, asking where the line of automation must be drawn. Includes a delegation matrix (what can be automated, assisted or must stay human), a quantified environmental footprint, a blinded survey of 10 dilemmas, case studies and regulatory proposals. Its conclusion is that human-in-the-loop is an engineering requirement. Published as a paper, slides and an interactive web platform.
`AI ethics` `EU AI Act`

---

## 🎓 Background

Bachelor's in Data Science and Engineering (GCED), Universitat Politècnica de Catalunya. Projects span the 2024–25 and 2025–26 academic years and were developed with classmates, who are credited in each repository.

## 🛠️ Topics I work with
Data engineering · Big data (Spark) · High-performance computing · Machine learning · Time series · Multivariate statistics · Optimization & algorithms · Graph and geospatial data · Responsible AI
https://www.linkedin.com/in/oriol-parent-ruiz-28946139a/
## 📫 Contact
- 💼 LinkedIn: [linkedin.com/in/oriolparent]((https://www.linkedin.com/in/oriol-parent-ruiz-28946139a/))
- 📧 Email: [parentruizoriol@gmail.com](mailto:parentruizoriol@gmail.com)
