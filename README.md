# Carré Nights
Léon Carré 1001 Nights illustrations with with accompanying excerpts from the J. C. Mardrus translation (French) and the E. P. Mathers translation (English). A script for automated generation of the anthology is provided.

For automated generation, the repository should at minimum initially contain the following files in the structure shown below:

```text
carre_nights/
├── document/
│   ├── illustrations/
│   │   └── volume_folder/
│   │   │   └── image_file.jpg
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