# 🏭 Smart Supplier: Optimizing Orders in a Fluctuating Market

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Overview

This project implements a reinforcement learning agent using dynamic programming to help a Smart Supplier optimize daily production decisions. The agent learns to maximize profit by making smart choices about which products to manufacture, considering:
- Limited raw materials
- Fluctuating market prices
- Daily demand changes
- Production constraints

## 🎯 Problem Description

### Scenario
A small Smart Supplier manufactures two products:
- **Product A**: High value, higher raw material cost
- **Product B**: Lower value, lower raw material cost

### Key Challenges
- Limited raw material (10 units per day)
- Market prices change daily
- Need to balance production between A and B
- Maximize profit over 5 days

### Market States
1. **High Demand for A**
   - Product A: $8 per unit
   - Product B: $2 per unit

2. **High Demand for B**
   - Product A: $3 per unit
   - Product B: $5 per unit

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- Git

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd smart-supplier
   ```

2. **Run the setup script**
   ```bash
   python setup.py
   ```
   This will:
   - Create a virtual environment
   - Install all dependencies

3. **Activate the virtual environment**
   ```bash
   # On Windows:
   .\.venv\Scripts\activate

   # On Unix/MacOS:
   source ./.venv/bin/activate
   ```

## 💻 Usage

1. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Dynamic_Programming_code_template.ipynb
   ```

2. **Run the Implementation**
   - Execute cells in sequence
   - View policy analysis
   - Check simulation results

## 📊 Features

- **Dynamic Programming Implementation**
  - Value Iteration algorithm
  - Optimal policy learning
  - State-value function calculation

- **Market Simulation**
  - Random market state transitions
  - Daily price fluctuations
  - Raw material management

- **Policy Analysis**
  - Production decisions visualization
  - Performance metrics
  - Policy optimization insights

## 📦 Project Structure

```
smart-supplier/
├── Dynamic_Programming_code_template.ipynb  # Main implementation
├── setup.py                                # Automated setup script
├── requirements.txt                        # Dependencies list
└── README.md                              # Documentation
```

## 📚 Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| NumPy | ≥1.21.0 | Numerical computations |
| Pandas | ≥1.3.0 | Data manipulation |
| Matplotlib | ≥3.4.0 | Data visualization |
| Jupyter | ≥1.0.0 | Interactive notebooks |
| IPython Kernel | ≥6.0.0 | Jupyter kernel |

## 🔧 Development

The `setup.py` script provides automated setup:
- Creates Python virtual environment
- Installs dependencies
- Cross-platform compatibility

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request 