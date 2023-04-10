# Local installation

## Intall `R` and its packages

```bash
sudo apt install r-cran-bookdown
```

## Install Python with a shared library

```bash
CONFIGURE_OPTS=--enable-shared pyenv install 3.10.6
```

## Install packages

```
python -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt
Rscript -e "library(reticulate); py_install('pandas==1.5.3')"
```

# Github deployement

![Settings](https://user-images.githubusercontent.com/7115035/230853603-cf01e5cc-e6de-4c44-9667-a7a82deffcbf.png)
