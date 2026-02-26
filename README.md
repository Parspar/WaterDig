This repository supports the Water Digitalization methods course for DigitaL Waters PhD pilot students. It contains structured code sprints designed to develop practical skills in environmental data analysis and computational workflows.

Course Overview

This course introduces core data science methods for environmental and water-related applications. Key themes include:

Reproducible scientific computing

Bash scripting for data organization

Git for version control

GitHub for collaboration and distribution

Open geospatial data sources and environmental datasets

Common spatial and temporal data structures

Supervised machine learning applications in R and Python

Development of reproducible computational pipelines

Repository organization and publication standards

Best practices for high-performance computing using a JupyterHub-based virtual research environment

The course emphasizes reproducibility, transparency, and scalable research workflows relevant to digital water systems and sustainable resource management.

How to Use This Repository

Log in to GitHub using your registered account.

Click Fork (top-right corner) to create your own copy.

Clone your fork to the DIWA DataLab using git clone.

Locate the assigned code sprint for the session.

Work through the exercises independently.

To submit your work:

git add

git commit

git push

Assignments and solution materials will be added weekly. During the course, you will practice synchronizing your fork with the upstream repository using pull and merge workflows.
Environment Setup

To run the notebooks properly, create a dedicated conda environment:

1. Create the environment
   conda create --prefix ~/conda-envs/waterdig

   2. Activate the environment

On a server:
source activate ~/conda-envs/waterdig
On a local machine:
conda activate ~/conda-envs/waterdig


3. Install required packages

   pip install -r requirements.txt

4. Register the environment as a Jupyter kernel

   python -m ipykernel install --user --name=waterdig --display-name "waterdig"

When opening notebooks in this repository, select “waterdig” as the active kernel from the top-right menu.

Citation

If these materials contribute to your research, please consider citing:
Wilson, G., Bryan, J., Cranston, K., et al. (2017). Good enough practices in scientific computing. PLOS Computational Biology, 13(6), e1005510.
https://doi.org/10.1371/journal.pcbi.1005510


