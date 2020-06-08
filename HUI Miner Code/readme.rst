High Utility Generators Mining
=========================================================

Simply make in the outside directory.

commands:

./ Optimizing-Revenue input/dataset input/unitProfit [min_util]

output format:

::

  /*Original Utility Database*/
  [Transac1 Util] | item1-1,util1-1
  [Transac2 Util] | item2-1,util2-1 item2-2,util2-2
  ============================================================
  <HUG1> [util1] [support1] [TWU1]
  <HUG2> [util2] [support2] [TWU2]

g++ -std=c++11 main.cpp Dataset.cpp Itemset.cpp ItemsetTable.cpp Items.cpp -o myprog
./myprog input/dataset input/unitProfit [min_util]

