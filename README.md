# From Clinical Event Logs to Narrative-Based Outcome Prediction with LLMs

**Roberto Nai, Emilio Sulis, Laura Genga and Adriana Boccuzzi**

---

This study explores a pipeline for transforming structured clinical event logs into narrative texts, with the aim of improving both human readability and downstream prediction of patient outcomes. Rather than treating hospital activity data as mere coded sequences, each patient trace is converted into a clinical story that embeds context such as triage severity, concurrent patient load, care shift, and day of the week. The narrative generation process is based on prompt‑based interaction with Large Language Models, with prompts carefully tuned to ensure semantic accuracy. Once the most reliable prompt formulation was selected, the entire dataset was leveraged to generate narrative representations for all patients.  
These narrative texts are then encoded using pre‑trained transformer models to produce fixed‑length embeddings, which serve as input to classifiers. This choice avoids costly fine-tuning and ensures computational efficiency and scalability, making the approach suitable for resource-constrained or rapid deployment settings.  
Applied to real-world emergency department data collected over a one-month period, the pipeline demonstrates how narrative episodes derived from event logs can bridge process mining and language processing, enabling outcome prediction in a format that is both informative and accessible for clinical reasoning.  

---

**Folder description**
- `article`: article presented at PODS4H 2025. 
- `images`: full resolution images. 

<!-- - `event_log`: event log (base and enriched via script). -->
  
---

**Related projects**  
Event log enrichment: [https://github.com/roberto-nai/HOSPITAL-EVENTLOG-ENRICHMENT](https://github.com/roberto-nai/HOSPITAL-EVENTLOG-ENRICHMENT).   
Event log to narrative prediction: [https://github.com/roberto-nai/HOSPITAL-EVENTLOG-NARRATIVE-PPM](https://github.com/roberto-nai/HOSPITAL-EVENTLOG-NARRATIVE-PPM). 

---

For questions or issues, please contact the project author [roberto.nai@unito.it](roberto.nai@unito.it).