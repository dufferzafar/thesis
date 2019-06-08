
1 Introduction

    1.1 Blockchain Systems (/ technology?)

    1.2 Bitcoin
        * Proof-of-Work
        * Chain forks & the problems they cause
 
        * Intro: Created, Nakamoto, Uses Proof-of-Work
        * Design / Protocols: BitP, TCP-RPCs
        * C++ build process (flags we used) etc.

2 Anchors

    * Definition
    * Structure

    * Generation
    * Propagation
    * Processing

    * Properties
        
3 Implementation

    3.1 Anchors in Bitcoin
        * Algorithms, Data structures

        * RPCs:
            * submitanchor
            * generateanchor

            * Code path diagrams?
    
    3.2 Test Bed for Experiments
        * Master / Slave architecture
            * 3 generations?

        * Txn Generation
            * Master used to send to all
            * Separate script
                * sendtoaddress
                * Tried using jmeter
                * sendmany

4 Experiments & Results

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

<!-- 5 Results  -->

5 Conclusion & Future Work
