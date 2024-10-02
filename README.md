# Natural Language Generation in NCB Languages

This is a project towards the **MSc Artificial Intelligence** degree at the **University of Cape Town**. It is part of a 3-component thesis, 
1. Development of a metric to measure the potential to adapt these algorithms between two languages.
2. Developing the algorithms (THIS).
3. Measuring correlation between 1. and 2. to validate the Metric developed in 1.
   
**Main Author/Student:** Phuthang Makhupane

This project focuses on Natural Language Generation (NLG) in NCB languages, specifically Zulu, Sotho, and Tswana. The goal is to develop algorithms that can verbalize various ontology axioms in these languages.

## Features

1. **Languages Supported**:
   - **Zulu** (existing)
   - **Sotho** (new)
   - **Tswana** (new)

2. **Ontology Axioms Verbalized**, with Description Logics symbology:
   - Subsumption: C ⊑ D
   - Negation: ¬C
   - Disjunction: C ⊔ D
   - Parthood: C ⊑ ∃R.D
   - Conjunction: C ⊓ D
   - And more...

3. **Test Ontology**:
   - The algorithms are tested using a test ontology that has been translated into each of the supported languages.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries (listed in `requirements.txt`)
