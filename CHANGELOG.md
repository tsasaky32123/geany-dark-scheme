# geany-dark-scheme Changelog

### 0.1 - inital release after migration to github

- Ran the google code exported tool, which migrated over the wiki articles and the issues.
- Manually moved all assets over to github, converted wiki pages to readme/changelog markdown files and checked everything into git.

## Google Code hosted Project

### geany_dark_filedefs_20100304_190847.tar.bz2
+ Added support for Markdown - .markdown (contributed by pho3nixf1re84, modified by Duncan Lock). I added the compiler option to this 'compiler=markdown "%f" > "%e".html' which will attempt compile your markdown file to filename.html using the default perl markdown script from John Gruber. I also set the default extension to .markdown
+ Added support for Nullsoft Scriptable Installer System scripts - .nsis (contributed by mr.soup12, modified by Duncan Lock). I adjusted the colours to fit the theme colours better.

### geany_dark_filedefs_20091119_234556.tar.bz2
+ Added support for Lua - .lua (contributed by curtstrangward)

### geany_dark_filedefs_20090927_201349.tar.bz2
+ Added support for Vala - .vala (contributed by boromil)
+ Added support for Docbook - .docbook (contributed by gmunkhbaatarmn)
+ Added support for yaml - .yaml (contributed by pho3nixf1re84)

### geany_dark_filedefs_20090516_193911.tar.bz2
+ Improved javascript support from etienne.deparis & ludwig.arne
+ Improved javascript in HTML support from T.Karbownicki

### geany_dark_filedefs_20090516_190439.tar.bz2
+ Added quick-and-dirty javascript support by Duncan Lock, partially based on (http://www.barryvan.com.au/2009/01/geany-ide-tango-dark-colour-scheme/)

### geany_dark_filedefs_20090516_182543.tar.bz2
+ Improved .php support - .php (improved by s5n43K3s)

### geany_dark_filedefs_20090516_181549.tar.bz2
+ Added support for C++ - .cpp - C++ (contributed by gtk.monkey) 
+ Added support for D - .d language files (contributed by gtk.monkey)
+ Added support for Haskel - .haskel (contributed by Dave.Sarman)
+ Added support for R stats language - .r (contributed by weibullguy) 

### geany_dark_filedefs_20081209_215628.tar.bz2
+ Added support for Latex - .latex page layout language (added by Enrico Tröger)

### geany_dark_filedefs_20081111_185356.tar.bz2
+ Added support for C# - .cs (can't remember where this came from)
+ Added support for c - .c (can't remember where this came from)

### geany_dark_filedefs_20080906_175251.tar.bz2
+ Initial version, including support for sql, sh, perl, conf, python, java, css, ruby & html - Most of these were originally developed by Roman Snitko, with contributions from Daniel Mlodecki (Javascript support in HTML), Paulo Cabido (C & Java), Nicolas Hainaux (Python) and me (C#, conf, sh & sql)
