# Learning Cassandra
This repository contains all my learning content on cassandra.

### Link to install cassandra on windows as one node cluster :

    - https://medium.com/@sushantgautam_930/simple-way-to-install-cassandra-in-windows-10-6497e93989e6

    - https://www.youtube.com/watch?v=EEXtVn3zAqc


### To run cassandra server (Run as admin) :

    cd C:\Program Files\apache-cassandra-3.11.6\bin
    cassandra.bat -f

### To run Cassandra query langugage shell :

    cd C:\Program Files\apache-cassandra-3.11.6\bin
    cqlsh

### To create keyspace :

    create keyspace cass WITH REPLICATION = { 'class' : 'SimpleStrategy', 'datacenter1' : 3 };

### Architecture of Cassandra :
    https://www.youtube.com/watch?v=ZM0wJ1suCUE&list=PL9ooVrP1hQOGJ4Yz9vbytkRmLaD6weg8k&index=5

### CAP Theorm :

    https://www.youtube.com/watch?v=ytPoGSNV8z8&list=PL9ooVrP1hQOGJ4Yz9vbytkRmLaD6weg8k&index=14

### Concepts to be known :

    1. Gossip Protocol -- https://www.edureka.co/blog/gossip-protocol-in-cassandra/
    2. Partition       -- https://www.youtube.com/watch?v=Soaod2WRmlg
    3. Snitch          -- https://www.youtube.com/watch?v=8XOYxelFzak 
    4. SS Table        -- http://distributeddatastore.blogspot.com/2013/08/cassandra-sstable-storage-format.html
    5. Tombstones      -- https://docs.datastax.com/en/dse/5.1/dse-arch/datastax_enterprise/dbInternals/archTombstones.html
    6. Compaction      -- https://www.youtube.com/watch?v=mTY3RdkzOuU

