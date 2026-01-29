# Machine Learning–Assisted Identification of Antimicrobial Resistance Patterns  
## in *Escherichia coli* and *Klebsiella pneumoniae*

### Author  
**Mukaram Ali**  
BSc (Hons) Medical Laboratory Technology

---

## 📌 Project Overview

This project presents a comparative analysis of phenotypic antimicrobial resistance (AMR) patterns in *Escherichia coli* and *Klebsiella pneumoniae* using large-scale, publicly available clinical susceptibility data.  

By integrating exploratory data analysis with classical machine learning techniques, this work investigates organism- and antibiotic-specific resistance trends relevant to clinical microbiology and antimicrobial stewardship.

📄 **Project Summary (PDF)**: *AMR_Comparative_Analysis_Summary.pdf*  
*[(To be added to this repository)](https://github.com/mukaram163/AMR-Comparative-Analysis/blob/main/AMR_Comparative_Analysis_Summary.pdf)*

---

## 🔬 Research Question

Can computational analysis of phenotypic antimicrobial susceptibility data reveal organism-specific resistance patterns in *Escherichia coli* and *Klebsiella pneumoniae* that are relevant to clinical microbiology and antimicrobial stewardship?

---

## 🧬 Background

Antimicrobial resistance (AMR) represents a major global health challenge, particularly among Gram-negative pathogens such as *E. coli* and *Klebsiella pneumoniae*. These organisms are common causes of both community- and hospital-acquired infections and are increasingly associated with multidrug resistance.

Although antimicrobial susceptibility testing is routinely performed in clinical microbiology laboratories, aggregated phenotypic data are often underutilized for broader resistance trend analysis. This project applies computational and machine learning–assisted approaches to extract biologically and clinically meaningful insights from large-scale susceptibility datasets.

---

## 📊 Dataset

Phenotypic antimicrobial resistance data were obtained from the  
**Bacterial and Viral Bioinformatics Resource Center (BV-BRC)** (formerly PATRIC), a curated and widely used public resource in AMR and microbial genomics research.

- **Organisms analyzed**:
  - *Escherichia coli*
  - *Klebsiella pneumoniae*
- **Data type**: Phenotypic antimicrobial susceptibility records
- **Total records analyzed**: >80,000

Raw datasets are not included in this repository and must be accessed directly from BV-BRC in accordance with their data usage policies.

---

## 🧪 Methods Overview

- Independent preprocessing of organism-specific datasets  
- Dataset harmonization and organism labeling  
- Exploratory data analysis of resistance distributions  
- Antibiotic-specific resistance profiling  
- Binary phenotype encoding (Resistant vs. Susceptible)  
- Classical machine learning–assisted feature analysis (logistic regression)

Machine learning is used strictly as an **analytical support tool**, not as a diagnostic or predictive clinical system.

---

## 📈 Key Findings

- *Klebsiella pneumoniae* exhibits significantly higher resistance rates than *Escherichia coli*  
- High resistance observed against **β-lactams** and **fluoroquinolones**  
- Relatively preserved susceptibility to **carbapenems** and **aminoglycosides**  
- Organism identity and antibiotic class are strong differentiators of resistance patterns  

These findings align with known resistance mechanisms and reinforce the clinical relevance of computational analysis for antimicrobial stewardship.

---

## ⚠️ Limitations

- Analysis is limited to phenotypic susceptibility data without genomic resistance markers  
- Potential sampling bias inherent to publicly available datasets  
- Intermediate susceptibility phenotypes were excluded from selected modeling steps  

---

## 🔮 Future Directions

- Integration of genomic AMR determinants  
- Temporal resistance trend analysis  
- Expansion to additional clinically relevant bacterial species  
- External validation of predictive models  

---

## 🧠 Purpose of This Project

This work was conducted as an independent, hypothesis-driven mini research project to demonstrate research readiness in microbiology and immunology, integrating clinical laboratory science with computational data analysis.

---
