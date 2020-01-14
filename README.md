# slic3r_make_tools

Use GNU Make and Slic3r to generate G-Code.

## Usage


- ```git clone https://github.com/jed-frey/slic3r_profiles.git ~/.Slic3r/make_tool```
- Copy ```~/.Slic3r/make_tool/Makefile``` to your folder with STLs.
- Run ```make``` in folder with STLs.
- G-code files are in ```build``` directory.

## ```slice_all.sh```

```slice_all.sh``` will slice STLs with all permutations of ```Slic3r``` settings.

## Examples

    cd  ~/.Slic3r/make_tool/examples
    make
