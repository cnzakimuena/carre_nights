# Carré Nights
Léon Carré 1001 Nights illustrations with accompanying excerpts from the J. C. Mardrus French translation (1900–1904) and the E. P. Mathers English translation (1986). A script for automated generation of the anthology is provided.

For automated generation, the repository should at minimum initially contain the following files in the structure shown below:

```text
carre_nights/
├── document/
│   ├── illustrations/
│   │   ├── volume_folder/
│   │   │   ├── image_file.jpg
│   │   │   └── ...
│   │   └── ...
│   └── References.bib
├── Carre_nights_starter.tex
├── Carre_nights_text.csv
├── generator.py
└── requirements.txt
```

installation:

```bash
pip install -r requirements.txt
```

usage:

```bash
python generator.py
```

![example image](figure.jpg)

### References

1. Mardrus, J. C. (Trans.). (1900–1904). Le livre des mille nuits et une nuit (Vols. 1–16). Éditions de la Revue blanche; Fasquelle.
1. Mathers, E. P. (Trans.). (1986). The book of the thousand nights and one night (J. C. Mardrus, Ed.). Routledge.