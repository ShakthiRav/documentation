# documentation

## requirements
Different branches of fabric-grabielle refer to different machines ( root ca ,  intermediate ca ect )  Ensure the content from each branch of the fabric-gabriele repository is in $GOPATH/src/github.com/hyperledger/ of the corresponding machine.

Both fabric & fabric-ca must also be cloned to $GOPATH/src/github.com/hyperledger/

## setup-fabric-network.sh

### preface
For the intial simple case we concern ourselves with , we include only 1 organisation (bt) alongside the orderer. This leaves 5 components involved : 
root ca 
intermediate ca
orderer
peer
run

Each of the above have a machine dedicated to them. We also have a separate machine which we will refer to as master ( since it corresponds to master branch)  . setup-fabric-network.sh is to be run on this master machine. It is 

### cleaning up

### setup procedure



#### start.sh 
