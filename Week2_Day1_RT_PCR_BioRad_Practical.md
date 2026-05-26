# Week 2, Day 1 — BioRad RT-PCR: First Sample Run (Practical)
**Date:** 06 May 2026  
**Institution:** ICMR-NJIL&OMD, Agra — COVID-19 Sampling Lab  
**Supervisor:** Dr. Ajay Vir Singh, Scientist F  
**Instrument:** BioRad RT-PCR Fluorescence Thermo Cycler (Advanced)  
**Detection:** SYBR Green (Dye-based)

## Objective
Run the first real cDNA sample on the BioRad RT-PCR 
machine. Learn plate setup, software navigation, 
result analysis, and contamination risk assessment.

---

## Part A — Machine Setup

**Step 1:** Switch on machine — lid opens upward 
(GROVES, not centre).  
**Step 2:** Switch on device computer connected through 
BioRad machine.  
**Step 3:** Check placement order of tubes as calculated.  
**Step 4:** Upon clicking software — it asks for 
detection type. Select **SYBR** (not PROBE, as we are 
using dye-based detection).  
**Step 5:** Window opens showing plate designation grid 
(rows A–E, columns 1–5).

---

## Part B — Plate Layout and Sample Naming

**Step 6:** Place tubes in **4th and 5th columns** — 
take cursor, select UP→DOWN to mark sample columns.

**Plate Layout Used:**

| Row | Col 1 | Col 2 | Col 3 | Col 4 | Col 5 |
|-----|-------|-------|-------|-------|-------|
| A   | .     | .     | .     | SYBR Btor act | SYBR Btor act |
| B   | —     | —     | —     | SIRT1 | SIRT1 |
| C   | —     | —     | —     | AKT   | AKT   |
| D   | —     | —     | —     | KOX1  | KOX1  |
| E   | .     | .     | .     | .     | .     |

**Step 7:** Upon selection in software — name each Box 
of rows/columns as primer names.  
**Step 8:** First select **"UNKNOWN"** from drop-down box.  
**Step 9:** ONE by ONE, select each one or two boxes 
(right-click A4, A5 both boxes), type name (e.g. SYBR), 
then click **LOAD** — name appears.  
**Step 10:** Repeat for each box until all naming is 
complete.  
**Step 11:** Select → Move → Protocol — check existing 
or create new (temp, cycles, etc.)

---

## Part C — Running the Machine

**Step 12:** Click **"Close the LID"** → Click **"RUN"**.  
**Step 13:** Process starts — wait for full process to 
complete, then perform analysis on results.

---

## Part D — Analysing Results

**Step 14:** Upon successful completion, a results table 
appears with Cq (quantification cycle) values:

| Well | Fluorescence | Target | Content | Sample | Cq |
|------|-------------|--------|---------|--------|----|

**Step 15:** If work plate is not as you set it up → 
first **replicate** it.  
**Step 16:** Study data — check PCR efficiency. You can 
change Cq threshold by dragging the black reference 
line up/down. 
⚠️ **CAUTION: NOT RECOMMENDED** — only do this to 
check efficiency, not to manipulate results.

---

## Part E — Contamination Risk Mitigation

**What is NTC?**  
NTC (No Template Control) = Negative template control. 
Input NTC as reference to check for contamination — 
NOT environmental contamination but cDNA contaminated 
with pollutants.

**If NTC spikes in PCR and behaves same as other 
standards/unknowns** → contamination suspected.

**How to verify legitimacy of UNKNOWN sample?**  
Use the **MELT CURVE**:
- The graph showing PEAKS at the temperature at which 
  cDNA breaks apart (denaturation)
- **If NTC melt curve = SAME as sample** → CONTAMINATED
- **If NTC melt curve = DIFFERENT** → RISK LOW — 
  sample is legitimate
  
## Connection to PhD Research
Running samples on the BioRad system directly mirrors 
the workflow for HsfA1 subgenome expression 
quantification. The NTC contamination check and melt 
curve validation are essential quality controls for 
any multi-gene, multi-primer RT-qPCR experiment. 
Understanding these now prevents data integrity 
problems in PhD-level experimental design.
