all: ../../bin/genzehn

../../bin/genzehn: genzehn.cpp
	g++ -Wall -Wextra -std=c++11 -I elfio-3.2 $^ -lboost_program_options -lz -o $@ || g++ -Wall -Wextra -std=c++11 -I elfio-3.2 $^ -lboost_program_options-mt -lz -o $@

clean:
	rm -f ../../bin/genzehn
