# cv-gen
LuaLaTeX script to parse a JSON CV into a LaTeX template.

## What it Does

It is common to use markup language such as the ubiquitous JSON to hold information for CVs an résumés. One format is the JSON file used in the [al-folio](https://github.com/alshedivat/al-folio) Jekyll academic website CV. However, converting this JSON to a finished PDF file can involve a lot of manual editing and updating. This simple LuaLaTeX script will parse the JSON file and produce a PDF CV in my preferred style, loosley based on [tucv](https://www.ctan.org/pkg/tucv). It should be simple to edit and change the style as needed.

## Requirements

- LuaLaTeX
- Biber (for bibliography generation)

## Limitations

- Currently only parsing the header (name, address, phone, email), education, and experience fields (more to come).
- Publications listed in `papers.bib` file are handled by Biber