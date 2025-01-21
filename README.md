# Design and Analysis of Algorithms for Top-K High-Utility Itemsets from Unstable Databases with Both Positive and Negative Utilities

## 📌 Project Overview
This project focuses on **High-Utility Itemset Mining (HUIM)**, specifically for **unstable databases containing both positive and negative utilities**. It introduces advanced algorithms for **Top-K High-Utility Itemset Mining (Top-K HUIM)** that enhance efficiency in memory utilization and computational performance.

We explore the challenges posed by traditional frequent itemset mining by incorporating **transaction probabilities, dynamic utility values, and pruning techniques** to handle real-world datasets efficiently.

## 📜 Abstract
Traditional **Frequent Itemset Mining (FIM)** methods fail to account for **item utility**, which includes both **positive (profit) and negative (loss) values**. Our approach extends **HUIM** with novel **pruning strategies** and **data structures** to efficiently mine valuable patterns while reducing computational overhead. The proposed algorithms are benchmarked against state-of-the-art techniques, demonstrating superior performance in real-world datasets such as **retail transactions, accident records, and market basket analysis**.

## 🚀 Key Features
- **Mining Top-K High-Utility Itemsets** without requiring a minimum utility threshold.
- **Handles both positive and negative utilities** (e.g., profits vs. costs/losses).
- **Advanced pruning strategies** to minimize search space and improve performance.
- **Tree-based and list-based data structures** for compact representation of transaction data.
- **Experimental validation** using real-world and synthetic datasets.

## 📁 Project Structure
```
├── algorithms/              # Implementation of algorithms
│   ├── algorithm1.py        # High Utility Pattern Mining with Transaction Probability (HUPT)
│   ├── algorithm2.py        # Revised Fast Tree (RFT)
│   ├── algorithm3.py        # Pattern Tree Remaining Utility (PTRU)
│   ├── algorithm4.py        # Trie-based Top-K Utility (TTUBU)
│   ├── algorithm5.py        # PU List Search (PUT)
│
├── data/                    # Datasets used for evaluation
│   ├── retail.csv           # Retail transaction dataset
│   ├── accident.csv         # Accident dataset
│   ├── kosarak.csv          # Kosarak dataset
│   ├── mushroom.csv         # Mushroom dataset
│
├── docs/                    # Documentation and report files
│   ├── report.pdf           # Research report
│   ├── work_assignment.pdf  # Work division among contributors
│
├── results/                 # Experiment results and analysis
│   ├── performance_plots/   # Charts and graphs for runtime/memory efficiency
│   ├── analysis.txt         # Summary of findings
│
├── README.md                # Project Documentation (this file)
├── requirements.txt         # Dependencies and installation requirements
└── main.py                  # Entry point for running the project
```

## 🛠️ Installation Guide
To set up the project locally, follow these steps:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Project
```bash
python main.py
```

## 📊 Algorithms Implemented

| Algorithm | Description |
|-----------|------------|
| **HUPT**  | High Utility Pattern Mining with Transaction Probability |
| **RFT**   | Revised Fast Tree Algorithm for Top-K Mining |
| **PTRU**  | Pattern Tree Remaining Utility Algorithm |
| **TTUBU** | Trie-based Top-K Utility with UBU pruning |
| **PUT**   | PU List Search Algorithm |

## 📌 Experimental Setup
Our experiments are designed to compare the performance of the proposed algorithms using real-world datasets. Metrics analyzed include:
- **Runtime efficiency** (execution time comparison)
- **Memory consumption** (space complexity analysis)
- **Scalability** across different dataset sizes
- **Effectiveness in mining Top-K patterns**

## 📚 Contributors
| Name               | Role                  |
|--------------------|----------------------|
| **Le Dang Nguyen** | Planning, Algorithm 1, Algorithm 3, Algorithm 4, Documentation |
| **Vo Gia Huy**    | Algorithm 2, Algorithm 5, Data Collection, Running Experiments |
| **Vu Ngoc Tra My** | Abstract, Introduction, Data Analysis, Result Visualization |

## 🏆 Results & Findings
- **Our proposed methods significantly outperform** existing HUIM approaches in terms of memory efficiency and computational performance.
- **The Top-K HUIM model reduces the need for manually setting a minimum utility threshold**, making it more flexible for practical applications.
- **Negative utility mining improves decision-making** in areas like financial risk management and retail promotions.

## 📌 Future Work
- Enhancing the algorithms to handle **real-time streaming data**.
- Exploring deep learning techniques for pattern recognition in **uncertain databases**.
- Extending the approach to **multi-dimensional high-utility itemset mining**.

## 📝 References
See **docs/report.pdf** for a detailed literature review and citations.

## 🎯 License
This project is licensed under the **MIT License**. See the LICENSE file for details.

---
> 🔥 _"Mining utility-based patterns is not just about frequency—it’s about value!"_

