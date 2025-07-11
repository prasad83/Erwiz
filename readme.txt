[Short story]
 
  ./erwiz ../examples/example1.txt ~/my-first-erd.png
 
[Long story]

  Open ./htmldoc/index.html in your browser for a complete
  documentation or just go into /bin and execute 
  
     ./erwiz ../examples/example1.txt ~/my-first-erd.png
     
  This reads the text file example1.txt located in the examples
  directory and converts it to a png raster image. 
  
  Other examples:
  
  	./erwiz ../examples/example1.txt ~/my-first-erd.jpg
  	./erwiz ../examples/example1.txt ~/my-first-erd.pdf
  	./erwiz ../examples/example1.txt ~/my-first-erd.svg
  	
  To make erwiz system-wide available create a symbolic link:
  
  	ln -s path/to/your/erwiz /usr/bin
  	
  Be sure to use the complete absolute path to erwiz.

  Graphviz (dot) should be installed as per your OS.
