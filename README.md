# Machine-Learning–Assisted Identification of Antimicrobial Resistance Patterns  
## in *Escherichia coli* and *Klebsiella pneumoniae*

### Author
Mukaram Ali  
BSc (Hons) Medical Laboratory Technology

---

## 📌 Research Question

Can computational and machine learning approaches identify clinically relevant antimicrobial resistance patterns in *Escherichia coli* and *Klebsiella pneumoniae* using large-scale phenotypic antimicrobial susceptibility data?

---

## 🧬 Background

Antimicrobial resistance (AMR) poses a major global health challenge, particularly in Gram-negative pathogens such as *E. coli* and *Klebsiella pneumoniae*. These organisms are frequently implicated in both community- and hospital-acquired infections and exhibit increasing resistance to commonly prescribed antibiotics.

While antimicrobial susceptibility testing is routinely performed in clinical laboratories, aggregated phenotypic data are often underutilized for understanding broader resistance trends. This project applies data-driven and machine learning techniques to explore resistance patterns across two clinically significant bacterial species.

---

## 📊 Dataset Source

Phenotypic antimicrobial resistance data were obtained from the  
**BV-BRC (formerly PATRIC) Antimicrobial Resistance Database**, a curated and widely used public resource in microbial genomics research.

- Organisms:
  - *Escherichia coli*
  - *Klebsiella pneumoniae*
- Data type: Phenotypic AMR records
- Total records analyzed: >80,000

Raw data files are not included in this repository and must be obtained directly from BV-BRC.

---

## 🧪 Methods Overview

- Independent exploration of organism-specific datasets
- Dataset harmonization and organism annotation
- Comparative resistance frequency analysis
- Antibiotic-specific resistance profiling
- Feature selection and binary classification (Resistant vs Susceptible)
- Use of classical machine learning models to support pattern identification

Machine learning is applied as an **analytical aid**, not as a diagnostic replacement.

---

## 📈 Key Findings

- *Klebsiella pneumoniae* exhibited a substantially higher proportion of resistant phenotypes compared to *E. coli*.
- High resistance rates were observed for commonly used antibiotics, including ampicillin and third-generation cephalosporins.
- Carbapenems and aminoglycosides demonstrated comparatively preserved susceptibility across organisms.
- Machine learning analysis supported organism- and antibiotic-specific resistance differentiation.

These findings are consistent with known clinical resistance mechanisms and highlight the relevance of computational analysis in antimicrobial stewardship.

---

## ⚠️ Limitations

- Analysis is limited to phenotypic susceptibility data without genomic resistance markers.
- Potential sampling bias inherent to publicly available datasets.
- Intermediate resistance phenotypes were excluded from certain modeling steps.

---

## 🔮 Future Directions

- Integration of genomic AMR determinants
- Temporal trend analysis
- Expansion to additional clinically relevant organisms
- Evaluation of predictive models using external validation datasets

---

## 🧠 Purpose of This Project

This work was conducted as an independent, hypothesis-driven mini research project to demonstrate research readiness in microbiology and immunology, integrating laboratory science with computational analysis.
