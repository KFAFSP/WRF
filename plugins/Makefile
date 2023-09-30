plugins: libplugin_rrtmg.so

include ../configure.wrf

libplugin_rrtmg.so: rrtmg.cpp
	$(CXX) $(FCDEBUG) -O3 -std=c++17 -fPIC -shared $< -o $@
