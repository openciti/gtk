GTK experiments
===

Compilation
---

./gtkcc foo foo.c 

or just ./gtkcc foo.c (will compile to foo)

see for details: https://developer.gnome.org/gtk3/3.2/gtk-getting-started.html

gtkcc is a helper for the following command: 

	gcc `pkg-config --cflags gtk+-3.0` -o foo foo.c `pkg-config --libs gtk+-3.0`

run `chmod +x makeln && chmod +x gtkcc && ./makeln gtkcc` to make gtkcc executable without the ./ prefix and from any directory
