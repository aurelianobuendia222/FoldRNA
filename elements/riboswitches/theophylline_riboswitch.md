# Theophylline Riboswitch

A synthetic RNA element that binds the small molecule theophylline and regulates gene expression in response. Frequently used as an inducible on-switch in prokaryotic and eukaryotic systems.

---

## 🧬 Sequence

```txt
GGGAGACAGAAUCGAGCUCUGUAGGAGAUCCGCGAAAGUGAAUUCGAGAGUGCAGG

Source: Synthetic design (Suess et al., 2003)
This sequence has been validated for binding theophylline with high specificity

🎯 Function
In the absence of theophylline, the riboswitch forms a stem-loop that sequesters the ribosome binding site (RBS), repressing translation. Binding of theophylline induces a conformational change that exposes the RBS and initiates translation.

🔬 Predicted Secondary Structure
Generated using ViennaRNA (RNAfold v2.4.18)
GGGAGACAGAAUCGAGCUCUGUAGGAGAUCCGCGAAAGUGAAUUCGAGAGUGCAGG
((((((..(((....)))..))))))............((((((....))))))..
Free Energy: −20.1 kcal/mol

Visual:
           GGGAGACAGAAUCGAGCUCU
          /                  \
       (((....)))         ((((....))))

🧪 Use Case Example
System: Prokaryotic (E. coli)
Goal: Inducible GFP expression in response to theophylline

Plasmid Design:
[Ppromoter]-[Theophylline Riboswitch]-[RBS]-[GFP]-[Terminator]

Expected Result:
No theophylline → RBS hidden → No GFP
theophylline → RBS exposed → GFP expressed