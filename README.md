# Heart Rate Variability Research 

Heart rate variability (HRV) research using Facebook AI Similarity Search (FAISS) to detect neonatal sepsis. 

Advised by Dr. Daniel Vasiliu.

# Abstract
__Research Purpose__: Neonatal sepsis is a leading cause of death in neonates. The current method of detecting sepsis is through a blood culture, which is invasive and time consuming. Heart rate variability (HRV) is a non-invasive method of detecting sepsis. The goal of this research is to analyze HRV data to improve on existing algorithms like the HeRO score which act as an early warning sign for NICU patients. 

# Methods
__Data__: The data in this research contains 2.5+ million vectors of HRV data. 

__FAISS__: FAISS is a library for efficient similarity search of vectors. As a preliminary step of this research we used FAISS to find the which healthy neonates have vectors most similar to the neonates that experienced sepsis. This provides an understanding of how differentiable the HRV data is between healthy neonates and neonates that experienced sepsis.