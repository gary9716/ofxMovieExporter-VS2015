1. put movieExporterExample under [openframeworks directory]\examples
2. use projectGenerator.exe to import this directory
3. delete generated ofApp.cpp and ofApp.h
4. add "$(OF_ROOT)\addons\ofxMovieExporter\libs\libav\lib\vs2010\*.lib" to 
Configuration Properties > Linker > Input > Additional Dependencies
5. rebuild solution