Unicode Rewriter is a Java tool which 
converts ID3 tags of MP3 files into Unicode. 
The reconverted MP3 files can be processed by 
iTunes and Rhythmbox



To clean the build
ant clean-build

To compile
ant compile

To build jar
ant dist

To build webstart package
ant webstart

To generate the java doc
ant doc 

To build everything
ant all

To clean everything
ant clean-all


To use IzPack
Update build.properties
Modify "compile" to point to the path of "compile"
compile = ~/opt/IzPack/bin/compile 