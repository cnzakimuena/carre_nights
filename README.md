# Carré Nights
Léon Carré 1001 Nights illustrations with accompanying excerpts from the J. C. Mardrus French translation (1959) and the E. P. Mathers English translation (2002). A script for automated generation of the anthology compatible with TeX v3.14159265 is provided.

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

1. Mardrus, J. C., & Fumaroli, M. (1959). Les mille et une nuits. Roissard.
1. Mardrus, J. C., & Mathers, E. P. (2002). The book of the thousand and one nights. Routledge.