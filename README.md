# HeXTeX

LaTeX templates.

## Usage

Get the files where they need to be:
```
cp -r src <your-new-latex-project>
```

Set the template you want (in file `main.tex`):
```
\input{<style>}

# ex. 
\input{paperstyle}
```

Build and enjoy:
```
make

# IF YOU CHANGE BIBLIOGRAPHY
make bib

# IF ALL IS LOST
make clean
make
```

__NOTE__: the content file is main.tex, this is also where compilation is
entered.

## Styles

| Style | Description |
|-------|-------------|
| paperstyle | Academic paper, math focused. |
| articlestyle | Academic paper, text focused. |
| bookstyle | Book. |
