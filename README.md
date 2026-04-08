# war-room-multi-agent-system
# War Room Multi-Agent Decision System

## Overview

This project simulates a cross-functional war room that analyzes product metrics and user feedback to decide whether to Proceed, Pause, or Rollback a feature rollout.

---

##  Setup Instructions

1. Install Python (3.8+ recommended)

2. Install required library:

```bash
pip install pandas
```

3. Clone the repository:

```bash
git clone https://github.com/aneeshvukantianeeseh/war-room-multi-agent-system.git
cd war-room-multi-agent-system
```

---

##  How to Run the Program End-to-End

1. Open Jupyter Notebook:

```bash
jupyter notebook
```

2. Open the file:

```
war_room_project.ipynb
```

3. Run all cells:

```
Kernel → Restart & Run All
```

4. The system will:

* Analyze metrics
* Evaluate sentiment
* Make decision
* Generate output

---

##  Example Command(s) to Reproduce Output

After running the notebook, output is saved at:

```
output/result.json
```

To view output inside notebook:

```python
import json

with open("output/result.json", "r") as f:
    data = json.load(f)

print(data)
```

---

##  Environment Variables

No environment variables are required for this project.

---

##  Output

The system generates:

* Decision (Proceed / Pause / Rollback)
* Rationale
* Risk Register
* Action Plan
* Communication Plan
* Confidence Score

---

## Tech Stack

* Python
* Pandas
* Jupyter Notebook
