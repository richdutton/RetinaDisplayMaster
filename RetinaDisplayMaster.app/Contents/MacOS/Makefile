###################################################################
#  Makefile for SetResX
#
#  Adapted from Redditor phoenix-dev
#  Arya McCarthy
#	 10 December 2014
###################################################################

CXX = g++
CXXFLAGS = 
SRC = main.mm SRApplicationDelegate.mm ResMenuItem.mm cmdline.mm utils.mm

SetResX: $(SRC)
	$(CXX) $(CXXFLAGS) $^ -o $@ -framework Foundation -framework ApplicationServices -framework AppKit 
#-L  -l MonitorPanel -undefined dynamic_lookup

clean:
	rm -f SetResX