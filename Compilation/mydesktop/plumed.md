How to compile PLUMED 

I cloned the git repository using the command:

git clone https://github.com/plumed/plumed2.git

I then configured using the command:

./configure --enable-modules=all --prefix /data/raquel/PLUMED

This command ensures that make install will put the plumed executable in the directory /data/raquel/PLUMED
