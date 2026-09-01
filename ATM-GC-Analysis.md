# Analytical Test Method: Quantitative Verification of Volatile Alcohol Content via Gas Chromatography (GC)
**Document ID:** ATM-ANL-667  
**Version:** 1.0  
**Effective Date:** August 31, 2026  
**Prepared By:** Peter Duncan, Technical Writer  

### 1.0 Purpose & Validation Principles
This method defines the analytical test parameters for separating and quantifying binary volatile alcohol mixtures using fractional thermal distillation followed by gas chromatography (GC) flame-ionization analysis. Compounds are resolved sequentially based on their unique thermal vapor pressures and stationary-phase retention characteristics. This protocol governs all downstream quality verification testing of Solution B product lots.

### 2.0 Equipment & Instrument Calibration
Prior to sample introduction, verify that the following system configurations are established:
*   **Separation Hardware:** Two (2) matching West condensers (one pre-packed with internal steel wool fractionation matrices), a vacuum adapter, a stillhead, a thermometer, and a 100 mL round-bottom flask.
*   **Analytical Hardware:** Gas Chromatograph (GC) unit equipped with an internal high-resolution column, a flame ionization detector (FID), and a dedicated 10 µL micro-syringe.
*   **Process Reagents:** GC Dilution Ether, Rinse Ether.

### 3.0 Experimental Separation & Sample Fractionation Procedure

#### 3.1 Thermal Fractional Distillation Execution
1.  **Charge Stillpot:** Measure exactly 50 mL of unknown alcohol mixture B and charge a clean 100 mL round-bottom flask. Add 4 boiling chips to suppress liquid bumping.
2.  **Assemble Fractional Column:** Secure the vertical steel-wool packed condenser directly above the stillpot without joint grease. Attach the secondary condenser to the recirculating coolant bath, ensuring full joint seals with standard Keck clamps.
3.  **Initiate Heat Profile:** Power the variable transformer heating mantle to an initialization setting of **35**. Allow the system to achieve baseline boiling parameters (approximately 25–40 minutes).
4.  **Extract Mid-Boiling Fraction (Fraction A):** Monitor the vapor phase drop-rate through the collection port. Once exactly 5.0 mL of liquid passes into the graduated cylinder, use a capillary tube to capture 3 drops of the live distillate. Transfer immediately to a vial labeled **Fraction A** and cap tightly.
5.  **Extract High-Boiling Tail (Fraction B):** Adjust the heating mantle to a maximum setting of **40** in small increments to maintain an even distillation pace. Capture 3 drops of final distillate once volume parameters cross 18 mL. Store sample in a vial labeled **Fraction B**.

#### 3.2 Chromatographic Sample Preparation & Injection Workflow
1.  **Prepare Dilutions:** Label three micro-test tubes as `A`, `B`, and `Mixture`. Pipette exactly 1.0 mL of GC Dilution Ether into each vessel.
2.  **Transfer Analytes:** Use clean glass capillaries to introduce 1 drop of Fraction A, Fraction B, and the raw stock alcohol mixture into their designated dilution tubes.
3.  **Purge Injection Syringe:** Flush the 10 µL micro-syringe five times with fresh rinse ether prior to sample upward draw to eliminate line contamination.
4.  **Inject Analyte:** Draw up exactly 1 µL of target solution into the syringe. Depress the needle fully into the GC injection port and trigger automated data acquisition software. Purge the syringe with rinse ether immediately following injection.

### 4.0 Data Analysis & Acceptance Calculations

#### 4.1 Calibration Correction Factors
To correct for density-induced fluctuations in raw peak integration parameters, calculate automated correction factors (\(CF\)) across the reference trace utilizing Isoamyl Alcohol (Peak C) as a fixed unity reference value (\(CF = 1.000\)):

\[\text{Correction Factor (CF)} = \frac{\text{Reference Peak C Area\%}}{\text{Target Peak Area\%}}\]

#### 4.2 Component Quantitation Formula
Determine the verified percentage composition of the volatile mixture by computing corrected areas (\(A_{corr}\)) for resolved peaks:

\[A_{corr} = \text{Raw Area Value} \times \text{Correction Factor (CF)}\]

\[\% \text{ Composition} = \frac{A_{corr, \text{Target}}}{\sum A_{corr, \text{Total}}} \times 100\%\]

*   **Acceptance Metric:** Lot B passes verification if final calculated metrics reflect an **84.80% concentration of 2-Methyl-1-propanol** and a **15.20% concentration of 2-Ethyl-1-butanol**.
