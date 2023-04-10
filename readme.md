<h1 align=center>DeVrouw <img src="https://github.com/AitSad/Static/blob/main/DeVrouw/woman%20waving.gif" height=35></h1>

DeVrouw is a dutch word reffering to "woman", not after the woman meme but to celeberate upcoming birthdate of mathematician Sophie Germain.  The library is useful for visualization and data analysis for beginners without using MatPlotlib and pandas together to write hectic scripts. Did you know? DeVrouw was entirely created by an AI system, and not even a single line, including this was written independently and copied from source! 

### Usage

```python
import devrouw.visualization as viz
import devrouw.analysis as ana

# Load data
data = ana.load_data('data.csv')

# Analyze data
mean = ana.calculate_mean(data)
median = ana.calculate_median(data)
mode = ana.calculate_mode(data)

# Visualize data
viz.plot_histogram(data)
viz.plot_boxplot(data)

# Print analysis results
print(f"Mean: {mean}")
print(f"Median: {median}")
print(f"Mode: {mode}")
```
