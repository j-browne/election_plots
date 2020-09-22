all: 2018_wi_assembly_elections.svg 2018_wi_assembly_elections.png

.PHONY: all clean

clean:
	rm -f 2018_wi_assembly_elections.svg 2018_wi_assembly_elections.png

2018_wi_assembly_elections.svg: 2018_wi_assembly_elections.gpi 2018_wi_assembly_elections.txt
	gnuplot 2018_wi_assembly_elections.gpi

2018_wi_assembly_elections.png: 2018_wi_assembly_elections.svg
	convert 2018_wi_assembly_elections.svg 2018_wi_assembly_elections.png
