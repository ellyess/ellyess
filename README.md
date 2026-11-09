## Ellyess Benmoufok

I build research software for wind energy and climate data. My PhD at Imperial College London (Computational Science & Data Science, 2026) was about making wind power models agree with what wind farms actually generate. I am based in London.

What I work on:

- **Correcting climate data against observations.** Reanalysis datasets such as ERA5 get the wind wrong in systematic, place-dependent ways. I learn corrections from observed generation and check where they help and where they do not.
- **Energy system modelling.** Wake losses, spatial resolution and their effect on where offshore wind gets built in European models.
- **Validation I would trust myself.** Held-out years, blocked cross-validation, pre-registered tests, and reporting the result that came back rather than the one I hoped for.

### Projects

| Project | What it is |
|---|---|
| [PyVWF](https://github.com/ellyess/PyVWF) | Python library that turns ERA5 reanalysis into bias-corrected wind power. Validated against observed generation in fifteen regions on four continents, with a public scorecard that says where the correction does not help. Tested, typed, documented, with a DOI per release. |
| [wind-generation-sources](https://github.com/ellyess/wind-generation-sources) | A catalogue of where to find observed wind generation data, country by country: 154 sources, 164 countries, with the licence and known traps for each. [Browse the map](https://ellyess.github.io/wind-generation-sources/). |
| [pypsa-eur-wind](https://github.com/ellyess/pypsa-eur-wind) | Research fork of the PyPSA-Eur energy system model: density-tiered wake losses, bias-corrected wind, and offshore resource resolution decoupled from the grid model. |
| [era5-windstorm-oasis](https://github.com/ellyess/era5-windstorm-oasis) | End-to-end run of the Oasis LMF PiWind example catastrophe model, plus an exposure sensitivity study. A reproduction for learning the hazard, vulnerability and financial modules, not a model of real risk. |
| [llm-persona-research](https://github.com/ellyess/llm-persona-research) | Do populations of LLM personas reproduce how real UK survey respondents split their opinions? Five persona methods, two models, and diagnostics for a model being right for the wrong reasons. |
| [WGAN-Regression](https://github.com/ellyess/WGAN-Regression) | Generative adversarial networks for probabilistic regression, from my MSc and the MOR-GANs paper, benchmarked against Gaussian processes and other baselines. |

### Publications

- Benmoufok et al. (2024). Improving wind power modelling through granular spatial and temporal bias correction of reanalysis data. *Energy*, 313, 133759. [doi:10.1016/j.energy.2024.133759](https://doi.org/10.1016/j.energy.2024.133759)
- Wang, Warder, Benmoufok et al. (2026). Geographic variability in reanalysis wind speed biases. *Energy Conversion and Management*, 352, 121066.
- Phillips et al., incl. Benmoufok (2022). Multi-Output Regression with Generative Adversarial Networks (MOR-GANs). *Applied Sciences*, 12(18), 9209. [doi:10.3390/app12189209](https://doi.org/10.3390/app12189209)

### Tools

Python (NumPy, pandas, Xarray, Dask, SciPy, scikit-learn, PyTorch), geospatial (GeoPandas, Rasterio, Cartopy, Google Earth Engine), pipelines (Snakemake, DuckDB, Docker), and pytest, GitHub Actions, ruff and mypy on everything I release. I develop with Claude Code, under rules and checks I wrote, and I own every scientific decision and release.

### Contact

[ellyess.com](https://www.ellyess.com) · [LinkedIn](https://www.linkedin.com/in/ellyessbenmoufok/) · [ORCID](https://orcid.org/0009-0000-0337-5690) · benmoufok.ellyess@gmail.com
