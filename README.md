# ns3.30.1_BlackHoleAttack

BlackHoleAttack performed on AODV routing protocol


(a) aodv-routing-protocol_basic.cc for every packet dropping behavior

(b) aodv-routing-protocol_advance.cc for alternate packet dropping behavior

Steps to follow :

1. Rename the choice of attack file to  aodv-routing-protocol.cc 
2. Simply copy the file and replace with the existing .cc and .h files in adov/model/
2. Copy the blackhole.cc and myapp.h to scratch folder.
3. Use " ./waf --run blackhole " command to execute the script.
