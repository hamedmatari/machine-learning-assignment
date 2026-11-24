# Linear Regression Programming Assignment, Part 1

The notebook predicts daily Capital Bikeshare rentals from normalized temperature. It compares polynomial degrees 1 through 15 using batch ordinary least squares. The original daily dataset is included at `data/day.csv`.

## Run the notebook

1. Open a terminal in the assignment directory, where `linear_regression.ipynb` and the `data` folder are located.
2. Create a Python 3 virtual environment and install the dependencies. The activation command below works in Bash and Zsh.

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install numpy pandas matplotlib notebook
   ```

3. Start Jupyter Notebook from the same directory.

   ```bash
   jupyter notebook
   ```

4. In the browser, open `linear_regression.ipynb` and choose **Kernel → Restart Kernel and Run All Cells**. Save the notebook to keep the refreshed outputs.

After installation, the notebook runs offline and loads `data/day.csv` by its relative path.

[Open the notebook](linear_regression.ipynb) · [Read the results in Persian](RESULTS.fa.md)
