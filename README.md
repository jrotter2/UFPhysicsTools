# UFHmmPhysicsTools
UF Physics Tools for Hmm Analysis.

These tools are organized into directories of `tools`, `selectors`, `analyzers`.


##Set Up
These tools are made to be used in a CMSSW Environment.
```
cmsrel CMSSW_10_6_19_patch2
cd CMSSW_10_6_19_patch2/src

cmsenv
```

Additionally, these tools depend on the NanoAOD tools. We can get these analysis tools and the NanoAOD tools and put them into our source directories of our CMSSW Environment.
```
git clone https://github.com/cms-nanoAOD/nanoAOD-tools.git PhysicsTools/NanoAODTools
git clone git@github.com:jrotter2/UFHmmPhysicsTools.git
```

Finally, we can run scram to compile all moduels.
```
scram b -j8
```

##Tools

##Selectors

##Analyzers
