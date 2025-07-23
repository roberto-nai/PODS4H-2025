# From Clinical Event Logs to Narrative-Based Outcome Prediction with LLMs

**Roberto Nai, Emilio Sulis, Laura Genga and Adriana Boccuzzi**

---

This study explores the interpretation of clinical processes by transforming structured event logs into narrative form. 
Instead of treating hospital event data as mere sequences of coded activities, we reframe each patient trace as a textual story, reflecting not only what happened but also how it might be communicated in natural language. These narratives are designed to capture both procedural context and situational urgency, integrating details such as triage severity, resources involved, and temporal patterns.
By converting event logs into narrative episodes, we enable new forms of interaction with clinical data, making it more intelligible and accessible to both humans and language-based systems. As a concrete application, we assess whether Large Language Models (LLMs) can infer the final patient outcome from these generated narratives.
We implement this pipeline using real-world data from a one-month hospital log from an Emergency Department. Several instruction-tuned LLMs, both proprietary and open-source, are used to simulate outcome prediction, and their responses are automatically evaluated against ground truth labels using standard classification metrics.
Rather than focusing exclusively on performance, this case study highlights the conceptual and communicative potential of narrative representations in healthcare process analysis. It opens up possibilities for narrative-driven reasoning in clinical decision-making and shows how structured data can be made more accessible and interpretable through natural language.

---

**Folder description**
- `images`: full resolution images
- `event_log`: initial event log
  

**Related projects**  
Event log enrichment: https://github.com/roberto-nai/HOSPITAL

---

For questions or issues, please contact the project author [roberto.nai@unito.it](roberto.nai@unito.it).
