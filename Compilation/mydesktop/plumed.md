# How to compile PLUMED 

I cloned the git repository using the command:

git clone https://github.com/plumed/plumed2.git

I did not switch to any other branch so I am working directly with the master version of PLUMEDI did not switch to any other branch so I am working directly with the master version of PLUMED.

Malachy then did a collection of magic that I did not understand.

I then configured using the command:

./configure --enable-modules=all --prefix /data/raquel/PLUMED

This command ensures that make install will put the plumed executable in the directory /data/raquel/PLUMED

I then compiled PLUMED on the four processors of my machine by using the command:

make -j 4

I then installed PLUMED into the directory /data/raquel/PLUMED by using the command:

make install

I then added the following line to my ~/.bashrc to make sure that PLUMED is in my path:

source /data/raquel/plumed2/sourceme.sh


