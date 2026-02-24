# TOPSIS Assignment – Conversational Models

## 📌 Task

Apply **TOPSIS** to find the best **pre-trained conversational model**.

---

## 🤖 Models Used

* DialoGPT
* BlenderBot
* GPT-2
* FLAN-T5

---

## 📊 Criteria Used

* Accuracy **(+)**
* Inference Time **(-)**
* Model Size **(-)**
* Memory Usage **(-)**

**Weights:** `[0.4, 0.2, 0.2, 0.2]`

---

## ⚙️ Steps Performed

1. Loaded dataset from `data.csv`
2. Normalized decision matrix
3. Applied weights and impacts
4. Calculated TOPSIS score
5. Ranked models
6. Generated graph

---

## ▶️ How to Run

Install libraries:

```
pip install -r requirements.txt
```

Run TOPSIS:

```
python topsis.py
```

Generate graph:

```
python plot.py
```

---

## 📁 Files

* `data.csv` – dataset
* `topsis.py` – TOPSIS code
* `plot.py` – graph code
* `result.csv` – output table
* `graph.png` – visualization

---

**Author:** Manmeet
