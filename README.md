# 🕸️ Ego Network — Imposter Center Detection

> **Computer Science Project** | Python | Graph Theory | Social Network Analysis

---

## 📌 Overview

A Python program that analyses **ego networks** from real-world social graph data and identifies **imposter ego centers** — nodes that appear to be ego centers but do not genuinely satisfy the structural properties of one.

The project applies graph theory concepts to the **Facebook Combined dataset**, a well-known benchmark in social network analysis research.

---

## ⚙️ How It Works

1. **Graph Loading** — Reads the `facebook_combined.txt` edge list to construct the social network graph
2. **Ego Center Extraction** — Identifies candidate ego centers from the network
3. **Imposter Detection** — Analyses the structural neighbourhood of each candidate to flag nodes that don't truly satisfy ego center criteria
4. **Output** — Returns the list of imposter ego centers from the provided set

---

## 🗂️ Project Structure

```
EgoNetwork/
├── egocenters.py            # Core logic: ego network construction & imposter detection
├── ego_test.py              # Test cases validating detection results
└── facebook_combined.txt    # Real-world Facebook social graph dataset (SNAP)
```

---

## 🛠️ Tech Stack

| Component | Tool |
|---|---|
| Language | Python 3.x |
| Graph Processing | NetworkX |
| Dataset | SNAP Facebook Combined |

---

## 🚀 Getting Started

```bash
pip install networkx
python egocenters.py
```

Run the test suite:
```bash
python ego_test.py
```

---

## 💡 Key Concepts Demonstrated

- **Ego network analysis** — understanding local network structure around individual nodes
- **Graph traversal & neighbour analysis** using NetworkX
- **Anomaly/imposter detection** in graph structures
- Working with real-world social network datasets

---

## 👤 Author

**Steve Parakal** | [GitHub](https://github.com/steveparakal)
