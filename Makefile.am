AUTOMAKE_OPTIONS = foreign subdir-objects 
SRC_DIR = src
bin_PROGRAMS = calculator
calculator_SOURCES = $(SRC_DIR)/calc.cpp $(SRC_DIR)/main.cpp $(SRC_DIR)/calc.hpp
AM_CXXFLAGS = -std=c++17

clean-all:
	@echo "Running a target clean-all"
	rm -rf autom4te.cache
	rm -f $(bin_PROGRAMS)
	rm -f /usr/local/bin/$(bin_PROGRAMS)
	rm -rf *.o $(SRC_DIR)/*.o
	rm -rf *.lo $(SRC_DIR)/*.lo
	rm -rf *.la $(SRC_DIR)/*.la
	rm -rf .deps $(SRC_DIR)/.deps
	rm -rf $(SRC_DIR)/.dirstamp
	rm -rf *.m4
	rm -rf configure
	rm -rf depcomp
	rm -rf install-sh
	rm -rf *.in
	rm -rf missing
	rm -rf config.*
	rm -rf Makefile
