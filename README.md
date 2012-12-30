# Default LaTeX

A collection of LaTeX templates and best-practices for bootstraping beautiful documents

## Exporting to PDF

Default LaTeX uses [The Ultimate LaTeX Makefile](http://www.acoustics.hut.fi/u/mairas/UltimateLatexMakefile/) to get rid of the shizz that generally comes with compiling LaTeX without a GUI.

Run ``make pdf`` to parse all .tex files in the directory and generate PDFs.

Now, we know that LaTeX is this naughty boy that produces a million trash files in the process of creating a single document. The more tolerant of us bear with the mess, while the more OCD of us religiously delete the files that defile the sancticity of their filesystems.

Run ``make clean`` to take out the trash.
