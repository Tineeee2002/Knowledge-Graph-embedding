# Knowledge-Graph-embedding

This repository contains a Python-based implementation of the TransE algorithm, [TransE](https://paperswithcode.com/paper/translating-embeddings-for-modeling-multi)

## Features
- Implement TransE embedding for Knowledge Graph (KG). 
- Use for relation prediction between 2 entities. (head and tail, in KG context).
## Getting Started

### Prerequisites
To run the notebook, you'll need:
- Python 3.7 or later
- Jupyter Notebook
- Libraries: `numpy`, `matplotlib`, `networkx`

Install the required libraries using:
```bash
pip install numpy matplotlib networkx
```

### Running the Notebook
1. Clone this repository:
2. Follow the instructions in the notebook to run for a sample graph or your own custom graph.

## How It Works
This algorithm will treat the relation (r) as a translation from head to tail in embedded space. So we will want h + r as closest to the t (or t is the nearest neighbor) for the link predition tasks.
![image](https://github.com/user-attachments/assets/6b25f8da-c129-4336-af5e-95b37e9eddce)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Enjoy exploring TransE with this implementation!


