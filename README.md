blockMeshDG
===========

hg-git cloned from https://code.google.com/p/blockmeshdg/ and adapted to blueCFD-Core 2.3.

Wiki page that gives more instructions on how to use this source code: http://openfoamwiki.net/index.php/Contrib_blockMeshDG

As for this repository at GitHub:

 * The `master` branch has the original source code, with the addition of this `README.md` and `LICENSE` file.

 * The `blueCFD-Core-2.3` branch has the code adapted to be easily compiled on blueCFD-Core 2.3. For more details, check the `README.md` file at [said branch](https://github.com/blueCFD/blockMeshDG/tree/blueCFD-Core-2.3).


Using in blueCFD-Core 2.3
=========================

 1. Start a new MSys terminal in blueCFD-Core 2.3.
 
 2. Run these commands for cloning the repository:
 ```
  user
  git clone https://github.com/blueCFD/blockMeshDG.git
  cd blockMeshDG
  git checkout blueCFD-Core-2.3
 ```

 3. Compile `blockMeshDG`, by running these commands:
 ```
  wmMC
  ./Allwmake
 ```
 
 4. Once finished, follow the usage instructions from the `blockMeshDG` wiki page: http://openfoamwiki.net/index.php/Contrib_blockMeshDG
 

Credits to
==========

 * Shui Pei
 * [dancfd](http://www.cfd-online.com/Forums/members/dancfd.html)
 * [Roamer](http://www.cfd-online.com/Forums/members/roamer.html) 
 * [akidess](http://www.cfd-online.com/Forums/members/akidess.html)

Check the commit history for more details: https://github.com/blueCFD/blockMeshDG/commits/master

License
=======

The same as OpenFOAM(R), namely GNU GPL v3. For more information, see the file LICENSE.

