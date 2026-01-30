# MBA Big Data course 2026

This repository contains the assignments for the course [Big Data Infrastructures & Technology ](https://studiegids.uva.nl/xmlpages/page/2025-2026/zoek-vak/vak/132939) part of the [Amsterdam Business School's MBA](https://studiegids.uva.nl/xmlpages/page/2025-2026/zoek-opleiding/opleiding/8420). The assignments are adapted from the course [Big Data](https://studiegids.uva.nl/xmlpages/page/2025-2026/zoek-vak/vak/130006), available at [this repository](https://github.com/hazourahh/big-data-course-2024-assignments)

## Installation

To get started, first clone this repository into your local machine.

```
git clone https://github.com/elidub/mba_bigdata_course26.git
```

If you're new to git, learn how to set up git [here](https://docs.github.com/en/get-started/quickstart/set-up-git). Alternatively, you can download the repository as a ZIP file and extract it: go to the repository page, click on the green "Code" button, and select "Download ZIP".

Next, make sure you have [Conda](https://docs.conda.io/en/latest/) installed. Then, let's create and activate the environment using the provided `env.yaml` file:

```bash
conda env create -f env.yaml
conda activate bigdata26
```

When using Jupyter notebooks, ensure you select the `bigdata26` kernel.

## Assignments

The assignments are in the notebooks `assignment-1.ipynb` to `assignment-4.ipynb`. Each notebook contains instructions and tasks to be completed. For assignments 2 to 4, solutions are provided in separate notebooks named `assignment_X_solution.ipynb`. As you are here to learn, you should try to solve the assignments on your own before consulting the solutions.

| Assignment | Solution | Description |
|------------|-------------|-------------|
| [Assignment 1](assignment_1.ipynb) | not applicable | Installation and setup verification. |
| [Assignment 2](assignment_2.ipynb) | [Solution 2](assignment_2_solution.ipynb) | SQL queries on a DuckDB database. |
| Assignment 3 | Solution 3 | _Work in progress_ |
| Assignment 4 | Solution 4 | _Work in progress_ |