# Andrés Alvear's Portfolio

Project portfolio of Andrés Alvear, an electronics engineer (M.Sc., Universidad de Chile) with over ten years of experience in FPGA signal processing, chip verification, and high-performance software development in Go and Python.

[LinkedIn](https://www.linkedin.com/in/andres-alvear-028bb01ba/) · [GitHub](https://github.com/andriu5)

## What's in the portfolio

### Case studies

Three projects documented in depth: the challenge, how I reached the solution, my contribution, results, and lessons learned.

| Case study | Period | In one line |
| --- | --- | --- |
| [MINI Radio Telescope Digital Spectrometer](case-mini.html) | 2015–2016 · Universidad de Chile | FPGA back-end that separates the sidebands of an 80–116 GHz receiver: over 40 dB of rejection, double the bandwidth, and first light on the Orion Nebula. |
| [Automated Validation of Formality ECO](case-fmeco.html) | 2023–2026 · Synopsys | Validation of every nightly build with Python ETL, an HPC farm and an AI agent; review time per cycle went from a full day to minutes. |
| [DegradIA: Corrosion Prediction](case-degradia.html) | 2025 · Universidad de Antofagasta | Go and Python platform that simulates steel corrosion in molten salt, validated against SEM-EDS (R² = 0.97), used at CDEA, and the origin of Novatherm Analytics. |

### Data Science

- **[Pima Indians Diabetes EDA](https://github.com/andriu5/EDA-pima-indians):** exploratory analysis of 768 patients and 8 clinical variables.
- **[Music Recommendation System](https://github.com/andriu5/music-recommendation-system):** benchmark of six recommendation approaches on the Million Song Dataset; the best model reaches F1 = 0.513.

### SDR radio from Santiago

[Step-by-step guides](radio/index.html) for my RTL-SDR station: setup, FM band sweeps with `rtl_power`, recording and decoding Meteor weather satellites, mapping ISDB-Tb digital TV channels, and IQ recordings for FPGA testbenches.

### Other projects

- **[Near-Earth Objects](https://github.com/andriu5/NEOs):** command-line tool to query near-Earth asteroid data.
- **[Meme Generator](https://github.com/andriu5/Meme_Generator):** Flask app and CLI that generate memes.
- **[Photodiode data logger](https://github.com/andriu5/photodiode_project):** quadrant detector for laser beam alignment.
- **[File Importer](https://github.com/andriu5/StrategyObject_FileImporter):** Strategy pattern prototype in Python 3.10.

## Repository layout

```
index.html            Homepage with all projects
case-*.html           Case studies
radio/                RTL-SDR station guides (standalone section, no JavaScript)
images/               Project images and diagrams
assets/               CSS, JS and fonts from the Massively template
elements.html,        Reference pages from the original template
generic.html
```

## Run it locally

It is a static site with no build step. From the repository root:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Credits

- **Design:** [Massively](https://html5up.net/massively) by [HTML5 UP](https://html5up.net) (AJ, [@ajlkn](https://twitter.com/ajlkn)), licensed under [Creative Commons Attribution 3.0](https://html5up.net/license). The original template has been modified: own content, new pages, and minor style changes.
- **Icons:** [Font Awesome](https://fontawesome.com).
- **Scripts:** [jQuery](https://jquery.com), [Scrollex](https://github.com/ajlkn/jquery.scrollex) and [Responsive Tools](https://github.com/ajlkn/responsive-tools).
- **NEOs card photo:** NASA on [Unsplash](https://unsplash.com).

## License

The Massively template is distributed under CC BY 3.0. Texts, case studies, diagrams and original photos are © Andrés Alvear. See [LICENSE.txt](LICENSE.txt) for details.
