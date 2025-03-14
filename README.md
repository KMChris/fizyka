# Notatki z Mechaniki Kwantowej

## Opis
Repozytorium zawiera notatki z wykładu "Podstawy Mechaniki Kwantowej" w formacie LaTeX. Główny plik `Notatki.tex` łączy wszystkie wykłady (`Wykład1.tex`, `Wykład2.tex`, itd.), tworząc pełny dokument PDF.

## Kompilacja
Aby wygenerować plik PDF z notatkami, należy użyć kompilatora `pdflatex`. W terminalu wykonaj:

```bash
pdflatex Notatki.tex
```

W razie potrzeby komenda ta może być wykonana wielokrotnie, aby poprawnie wygenerować spis treści oraz odnośniki.

## Struktura repozytorium
- `Notatki.tex` – główny plik łączący wszystkie wykłady
- `Wykład1.tex`, `Wykład2.tex`, ... – poszczególne pliki z treścią wykładów
- `Notatki.pdf` – wynikowy dokument PDF
- `images/` – katalog na pliki graficzne używane w notatkach

## Wymagania
Aby skompilować dokument, należy mieć zainstalowany system LaTeX. Zalecana jest dystrybucja TeX Live, ale można również skorzystać z innych, takich jak MikTeX (Windows) czy MacTeX (macOS).
