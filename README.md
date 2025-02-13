# RNA-seq-DEG-Analysis
A bioinformatics project performing differential gene expression (DEG) analysis on RNA-seq data using Python.
# RNA-seq DEG Analysis - Differential Gene Expression in RNA-seq Data

##  Overview
This project analyzes **differential gene expression (DEG) in RNA-seq data** using **Python & Jupyter Notebook**. It applies statistical methods to identify significantly upregulated and downregulated genes between experimental and control conditions.

### **Key Features:**
✅ **Preprocessing & Normalization**: Log2(TPM+1) transformation, low-expression gene filtering  
✅ **DEG Analysis**: Log2 Fold Change (log2FC), T-test, FDR correction  
✅ **Visualization**: Volcano Plot for significantly differentially expressed genes  
✅ **Biomedical Insights**: Identified immune-related genes potentially linked to inflammation  

---

##  Results & Findings
- **1735 significantly differentially expressed genes (DEGs) identified**.
- **More upregulated genes** in the experimental condition, suggesting **potential immune activation**.
- **Key Upregulated Genes**:
  - **IGHG1 (log2FC = 5.48)** → Involved in immune response
  - **JCHAIN (log2FC = 4.77)** → Potentially linked to antibody production
  - **IFI27 (log2FC = 3.75)** → Related to immune activation
- **Fewer downregulated genes**, indicating most genes are maintained or upregulated.

##  ** Volcano Plot:**
