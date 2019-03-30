# Install pydot and graphviz  
sudo apt install python-pydot python-pydot-ng graphviz 

# create a test file  
e.g test.dot 
dot -Tpng -O test.dot
# open the generated png
xdg-open test.dot.png &
# Try other options of graph type
neato -Tpng -O test.dot  
circo -Tpng -O test.dot
