
1 Introduction

    1.1 Blockchain Systems (/ technology?)
        * Proof-of-Work
        * Chain forks & the problems they cause
 
    1.2 Bitcoin
        * Intro: Created, Nakamoto, Uses Proof-of-Work
        * Design / Protocols: BitP, TCP-RPCs
        * C++ build process (flags we used) etc.

    1.3 Anchors
        * What are they
        * How they could help (motivation)
        
2 Implementation

    2.1 Anchors
        * Algorithms, Data structures

        * RPCs:
            * submitanchor
            * generateanchor

            * Code path diagrams?
    
    2.2 Test Bed
        * Master / Slave architecture
            * 3 generations?

        * Txn Generation

3 Experiments

    * Setup
        * Baadal machines
            * 1 master, 19 slaves
            * Specs of each machine

        * Network Topology

        * Delays
            * Table taken from 
            * 

    * Fork Resolution Times

    * Propagation Times
        * Blocks
        * Anchors

    * Block Sizes

4 Results & Conclusion

Also, should I only write about our final design? or should I also go into things that we tried but didn't work out (like JMeter etc.)
