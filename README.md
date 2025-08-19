
# Judo Sharks – Hugo + Ananke (PL)

**Docelowa ścieżka katalogu głównego:** `/app/git/judo-sharks`

## Szybki start (Linux/macOS)

```bash
# 1) Skopiuj projekt do /app/git/
sudo mkdir -p /app/git && sudo chown -R $USER:$USER /app/git
unzip judo-sharks-ananke.zip -d /app/git/
cd /app/git/judo-sharks-ananke/judo-sharks-ananke  # (wejdź do folderu projektu)

# 2) Zainicjuj moduły i pobierz motyw Ananke
hugo mod init judosharks.local/judo
hugo mod get github.com/theNewDynamic/gohugo-theme-ananke

# 3) Uruchom serwer developerski
hugo server -D
```

## Podmiana grafik
- **Logo:** plik `static/images/judo-sharks.png` (już ustawione w `config.toml` jako `site_logo`).
- **Hero:** plik `static/images/hero-judo.jpg` – możesz podmienić na własne zdjęcie dzieci w judogach.
- **Galeria:** pliki `static/images/galeria-*.jpg`

## Gdzie edytować treści
- Strona główna: `content/pl/_index.md`
- O klubie: `content/pl/o-klubie/_index.md`
- Trenerzy: `content/pl/trenerzy/_index.md`
- Grupy: `content/pl/grupy/_index.md`
- Grafik: `content/pl/grafik/_index.md`
- Aktualności: `content/pl/aktualnosci/`
- Galeria: `content/pl/galeria/_index.md`
- Kontakt: `content/pl/kontakt/_index.md`
