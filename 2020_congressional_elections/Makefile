all: 2020_congressional_elections.svg 2020_congressional_elections.png

.PHONY: all clean

clean:
	rm -f 2020_congressional_elections.svg 2020_congressional_elections.png

2020_congressional_elections.svg: 2020_congressional_elections.gpi 2020_congressional_elections.txt
	gnuplot 2020_congressional_elections.gpi

2020_congressional_elections.png: 2020_congressional_elections.svg
	convert 2020_congressional_elections.svg 2020_congressional_elections.png
