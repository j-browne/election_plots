all: 2016_presidential_election.svg 2016_presidential_election.png

.PHONY: all clean

clean:
	rm -f 2016_presidential_election.svg 2016_presidential_election.png

2016_presidential_election.svg: 2016_presidential_election.gpi 2016_presidential_election.txt
	gnuplot 2016_presidential_election.gpi

2016_presidential_election.png: 2016_presidential_election.svg
	convert 2016_presidential_election.svg 2016_presidential_election.png
