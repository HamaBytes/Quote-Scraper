# Quote Scraper

Scraper éthique de citations avec CLI et interface web.

## Installation
```bash
# Cloner le repo
git clone https://github.com/username/quote-scraper.git
cd quote-scraper

# Créer environnement virtuel
python -m venv venv
venv\Scripts\activate  # Windows

# Installer dépendances
pip install -r requirements.txt
```

## Usage

### CLI
```bash
python -m cli.main --limit 20 --tag love --output quotes.json
```

### Web App
```bash
python -m web.app
```

## Features
- ✅ Scraping multi-sources
- ✅ Respect robots.txt
- ✅ Rate limiting éthique
- ✅ Export JSON/CSV
- ✅ CLI & Web interface

## Technologies
- Python 3.10+
- BeautifulSoup4
- Flask
- Bootstrap 5

## Structure
```
quote-scraper/
├── core/          # Logique métier
├── cli/           # Interface CLI
├── web/           # Application web
└── tests/         # Tests unitaires
```

## License
MIT