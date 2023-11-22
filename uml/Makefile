SOURCES=$(wildcard *.txt)
LATEX=$(SOURCES:%.txt=%.latex)
#	SOURCES=$(addprefix src/,foo bar)
# -verbose
all: $(SOURCES)
		java -jar /opt/plantuml/plantuml.jar -tlatex $^;
		rename .latex .tex *.latex