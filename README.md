

**A mathematical model of the pancreatic duct cell generating high bicarbonate concentrations in pancreatic juice**   
David C Whitcomb, G Bard Ermentrout, _Pancreas_ 2004 29:e30-40; PubMedID:
[15257112](http://www.ncbi.nlm.nih.gov/pubmed/15257112)

Abstract:  
**OBJECTIVE:** To develop a simple, physiologically based mathematical model of pancreatic duct cell secretion using experimentally derived parameters that generates pancreatic fluid bicarbonate concentrations of >140 mM after CFTR activation.   
**METHODS:** A new mathematical model was developed simulating a duct cell within a proximal pancreatic duct and included a sodium-2-bicarbonate cotransporter (NBC) and sodium-potassium pump (NaK pump) on a chloride-impermeable basolateral membrane, CFTR on the luminal membrane with 0.2 to 1 bicarbonate to chloride permeability ratio. Chloride-bicarbonate antiporters (Cl/HCO3 AP) were added or subtracted from the basolateral (APb) and luminal (APl) membranes. The model was integrated over time using XPPAUT.   
**RESULTS:** This model predicts robust, NaK pump-dependent bicarbonate secretion with opening of the CFTR, generates and maintains pancreatic fluid secretion with bicarbonate concentrations >140 mM, and returns to basal levels with CFTR closure. Limiting CFTR permeability to bicarbonate, as seen in some CFTR mutations, markedly inhibited pancreatic bicarbonate and fluid secretion.   
**CONCLUSIONS:** A simple CFTR-dependent duct cell model can explain active, high-volume, high-concentration bicarbonate secretion in pancreatic juice that reproduces the experimental findings. This model may also provide insight into why CFTR mutations that predominantly affect bicarbonate permeability predispose to pancreatic dysfunction in humans. 

This SBML version of the model was created directly from the XPPAUT code found
in the appendix with the exception of the parameter **vr** , the ratio between
the duct cell volume and the duct lumen, which is defined inversely to the
main text in the XPPAUT code. **vr** was defined as the ratio of the duct cell
volume to the duct lumen volume as in the main text. The model reproduces the
figures found in the article. The model uses initial assignments for the lumen
volume and events to trigger CFTR opening, so only tools supporting these
features can be used to simulate it (eg. Copasi and SBW/Roadrunner).

