# Sports Analytics Club — Workshop 2

Classical machine learning with the Sports Analytics Club at UT Dallas. Choose one sport to get started.

## Open your notebook in Google Colab

| Sport | Notebook | Activity |
|---|---|---|
| Football | [Football notebook](notebooks/football_notebook.ipynb) | Linear Regression |
| Soccer | [Soccer notebook](notebooks/soccer_notebook.ipynb) | Logistic Regression |
| Basketball | [Basketball notebook](notebooks/basketball_notebook.ipynb) | K-Means, with optional PCA |

1. Download your chosen notebook.
2. Open [Google Colab](https://colab.research.google.com/) and choose **File → Upload notebook**.
3. Connect to a **CPU** runtime and work from top to bottom.
4. Complete the **Edit this cell** tasks, then run the **Run this cell** sections as provided. Save your own copy.

Each notebook works independently and includes its dataset. No data upload or local Python installation is needed.

## Datasets and slides

The prepared datasets are in `data/`: [football](data/nfl_data.csv), [soccer](data/soccer_data.csv), and [basketball](data/nba_data.csv).

[Workshop slides](slides/Workshop2_Slides.pptx)

## Data credits

- **Football:** [nflverse schedules](https://github.com/nflverse/nfldata), NFL 2017–2024; prepared pregame scoring-history features.
- **Soccer:** Wyscout, Pappalardo & Massucco (2019), [Soccer match event dataset](https://doi.org/10.6084/m9.figshare.7770599.v1), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Adapted EPL 2017–18 shot subset with derived features; not an endorsed Wyscout product.
- **Basketball:** [SportsDataverse / ESPN box scores](https://github.com/sportsdataverse/sportsdataverse-data/releases/tag/espn_nba_player_boxscores), NBA 2023–24; prepared player-season rates.

