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

## 📈 Results (Tables & Graphs)

### ✔ Result Table

The TOPSIS scores and ranking of models are saved in:

```
result.csv
```

This table shows the calculated score and final rank of each conversational model.

Model,Accuracy,Time,Size,Memory,Score,Rank
DialoGPT,0.88,140,500,2.3,0.4038338822343754,3.0
BlenderBot,0.91,160,600,2.6,0.162086065647148,4.0
GPT-2,0.85,110,350,1.9,0.7946233611819546,1.0
FLAN-T5,0.93,150,480,2.2,0.46623399983775665,2.0


### ✔ Graph Visualization

The comparison graph generated from TOPSIS scores is shown below:


![TOPSIS Graph](graph.png)

The graph visually compares all models based on their TOPSIS score to help identify the best model.

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
* `topsis.py` – TOPSIS implementation
* `plot.py` – graph generation
* `result.csv` – output table
* `graph.png` – visualization

---

**Author:** Manmeet
