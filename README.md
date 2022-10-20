# Tesseract - API de Serviços

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/claimfy/cfy-infinity-arc">
    <img src="https://raw.githubusercontent.com/claimfy/claimfy/main/images/eye-of-agamotto-pixel-art.png" alt="Logo" width="80" height="60">
  </a>

  <h3 align="center">Data of Agamotto</h3>

</div>

## Description

A Claimfy API tem por objetivo funcionar como uma interface para obtenção de dados oriundos, principalmente, da DBJus e demais fontes externas a Claimfy.

#### Fontes de Dados
- DBJus (Em integração)

## Getting Started

### Dependencies

#### Requirements

- poetry


## Instalação

```sh
cd apps/tesseract
poetry install
```

On linux

```
sudo apt-get install wkhtmltopdf -- devido o uso da lib pdfkit
```

## Execução

```sh
cd apps/tesseract
poetry run python tesseract/main.py
```

---

Made with ♥ by Claimfy (https://github.com/claimfy)
​

