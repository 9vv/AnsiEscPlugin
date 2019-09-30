http://www.drchip.org/astronaut/vim/index.html#ANSIESC

This plugin follows Ansi-escape sequences to colorize subsequent text using vim's syntax
highlighting engine.

The AnsiEsc plugin provides a single command: :AnsiEsc , which will toggle Ansi-escape
sequence processing. When enabled, AnsiEsc will handle <esc>[FGm, <esc>[ATTR;FGm, and
<esc>[FG;BGm sequences; subsequent text will then be colored appropriately.

With vim 7.2 and earlier, the escape sequence itself will take space but will be
suppressed using "Ignore" highlighting. Vim 7.3 comes with Vince Negri's
conceal/ownsyntax capabilities built-in. With it, Ansi-escape sequences will have their
colorizing effects but will themselves be concealed (again, when AnsiEsc is enabled and
one has used set conceallevel=[2 or 3]). Also available at vim.sf.net where you may rank
it. 
