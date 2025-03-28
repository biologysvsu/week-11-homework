# Week 11 Homework – Gene Expression Analysis in R

### Objectives

In this assignment, you will analyze differential gene expression between **mock-treated** and **COVID-infected** samples using real RNA-seq count data. You will:

- Use DESeq2 to identify differentially expressed genes.
- Generate a volcano plot.
- Identify one **upregulated** and one **downregulated** gene.
- Investigate each gene using [Ensembl](https://useast.ensembl.org/index.html).
- Hypothesize why each gene may be regulated in response to SARS-CoV-2.

---

### Files Provided

- `counts.txt` – Raw gene count data.
- `geneexpression.R` – Pre-written R script for your analysis.

## Step-by-Step Instructions

### 1. **Set Up Your Project**
- Open **RStudio**.
- Go to: `File > New Project > New Directory > New Project`.
- Make sure you know where you are saving your project.
- Name your project: `week-11-homework`.
- Click **Create Project**.

### 2. **Download Files from GitHub**
From this GitHub repository:
- `counts.txt`
- `geneexpression.R`

Download these files and move them into your newly created R project folder.

### 3. **Run the Analysis**
- In the **Files** pane (bottom-right of RStudio), click on `geneexpression.R` to open the script.
- Run the script using **Ctrl + Shift + Enter** or by clicking **Source**, or by selecting the whole scrip `ctrl+A` and clicking the `run` button.

This script will:
- Run a DESeq2 analysis.
- Automatically generate and save two volcano plots:
  - `volcano_plot.png`
  - `volcano_plot_labels.png`
- List significantly up- and downregulated genes.

---

## Your Tasks

### 1. **Insert Volcano Plot**
- Open `volcano_plot_labels.png` from the **Files** pane.
- Copy and paste the plot into your homework document.
- Add a **legend/caption** as if you were submitting it for a scientific journal. Example (don't just copy and paste this example, please):
  > **Figure 1.** Volcano plot of differential gene expression between mock-treated and SARS-CoV-2–infected samples. Red dots represent significantly upregulated genes (log2FC > 1, padj < 0.05); blue dots represent downregulated genes (log2FC < -1, padj < 0.05); gray dots are not significant.

---

### 2. **Gene Selection**
- From the list of genes displayed at the end of the R script (`top_genes`), select:
  - **One significantly upregulated transcript**
  - **One significantly downregulated trnascript**
  - It is very unlikely that you and your peers will select the exact same combination of genes. Your gene selections should reflect your own analysis and Interpretation of the volcano plot. Please submit individual responses.

### 3. **Search Ensembl**
- Search for both genes using the [Ensembl Genome Browser](https://useast.ensembl.org/index.html). Looks for their function.

### 3. **Answer homework questions**
- Add your volcano plot
- Answer howework questions
- Submit homework file on canvas by due date
