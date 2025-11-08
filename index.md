---
layout: default
title: Methodology Assignment 4 — Task 2
---

# Quarter 2 Project Brainstorm

**Name / Email:**  
Ryan Cao — [rycao@ucsd.edu](mailto:rycao@ucsd.edu)

**Section / Mentor:**  
Section B23 — Justin Eldridge / Solix

---

## Brainstorm Prompts for Q2 proposal

**1. What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic we explored this quarter was **extracting insights from patient–doctor dialogue**.  
This topic is interesting to me because it connects language understanding with healthcare impact.  
Routine clinical conversations contain a well of implicit information about patients’ medical histories, medications, and ongoing concerns, yet this data is often underutilized and seen as mundance interactions.  
By converting these dialogues into structured insights, we can help clinicians identify emerging issues, track medication usage, and improve patient outcomes.  




**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For my Quarter 2 Project, I would like to extend our previous work by exploring a **Graph Neural Network (GNN)** model that integrates **medical ontologies** to enhance understanding of patient–doctor dialogue data.  
In this framework, domain-specific ontologies—such as those defining relationships between diseases, symptoms, and treatments—would serve as structured prior knowledge.  
By embedding these ontologies into a GNN, the model could learn how medical concepts interact and influence each other within real-world conversations.  
This integration would help the model contextualize patient dialogue in terms of established clinical knowledge, improving its ability to infer use-case effects such as treatment outcomes or medication relevance.  
The project would focus on developing and evaluating this ontology-informed GNN pipeline, leveraging existing dialogue data and pre-trained embeddings.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**  
During Quarter 1, we explored a wide range of ideas and performed several replication studies to understand different applications of AI in drug discovery.  
While this breadth gave us valuable exposure to various modeling strategies, it also limited our ability to develop a cohesive research direction.  
For Quarter 2, I would like to narrow our focus to a single, well-defined area—such as applying graph-based models for knowledge integration in 
This shift from exploration to specialization would allow for more rigorous experimentation, clearer evaluation metrics, and a more substantial contribution to our chosen subdomain of AI in drug discovery.
Instead of doing mini replications we should pursue a singular idea at a more granular level.



**4. What other techniques would you be interested in using in your project?**  
To support our focus on graph-based models for biomedical knowledge integration, I would like to explore techniques that improve the way information is represented and propagated within graphs.  
Specifically, I’m interested in experimenting with **knowledge graph embeddings** and **node feature augmentation** using pretrained biomedical language models such as BioBERT or ClinicalBERT.  
These methods could help bridge the knowledge gap between unstructured patient–doctor dialogue and structured ontology data by aligning textual entities with their graph representations. We can essentially give our model medical meanings behind interactions like "I'm experiencing XYZ symptoms and I am currently taking X medication"- Patient.  
Additionally, I’d like to explore **attention-based message passing** within Graph Neural Networks to identify which ontology relationships are most influential in downstream predictions.  



