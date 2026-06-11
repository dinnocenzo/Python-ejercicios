# Python-ejercicios

A collection of Python exercises focused on number system conversions and algorithms, implemented and demonstrated interactively using Jupyter Notebooks.

## Tech Stack

- Python 3
- Jupyter Notebook

## Project Structure

```
Python-ejercicios/
├── Ejercicios.ipynb    # Main notebook with exercises and solutions
├── requirements.txt    # Python dependencies
├── .gitignore          # Git ignore rules
├── LICENSE             # MIT License
└── README.md           # Project documentation
```

## Setup / Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/dinnocenzo/Python-ejercicios.git
   cd Python-ejercicios
   ```

2. **Create and activate a virtual environment** (recommended)

   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

## Usage

Open `Ejercicios.ipynb` in Jupyter Notebook. The notebook contains several implementations of number system conversion algorithms, including:

- **Integer to Binary** — multiple approaches to converting a positive integer to its binary representation (e.g., `aBinario(25)` returns `11001`)
- **Fractional Decimal to Binary** — converting a decimal fraction to binary (e.g., `fraccion_a_Binario(1/3)` returns `'0.010101...'`)
- **Mixed Decimal to Binary** — converting a number with both integer and fractional parts using `math.modf` (e.g., `decimalToBinari(25.3125)` returns `11001.0101`)

Each algorithm is accompanied by inline explanations and example outputs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
