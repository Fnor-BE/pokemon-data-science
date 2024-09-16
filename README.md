<h1 align="center">
  <br>
  <img src="images/logo.png" alt="Pokemon Visualization">
  <br>
</h1>

<h4 align="center">Data visualization using Pokémon</h4>

## Technologies

The script uses [Python](https://www.python.org/) inside a [Jupyter Notebook](https://jupyter.org/). It relies on the following modules:

* Pandas
* Numpy
* Matplotlib
* Seaborn

## Data Sources

This project directly imports the data from my [Pokémon Data Scraper Project](https://github.com/Fnor-BE/pokemon-data-scraper).

```python
import pandas as pd

# Pokemon data
df = pd.read_csv('https://raw.githubusercontent.com/Fnor-BE/pokemon-data-scraper/main/pokemons.csv')
# Type chart
df_types = pd.read_csv('https://raw.githubusercontent.com/Fnor-BE/pokemon-data-scraper/main/pokemon-type-chart.csv')
```