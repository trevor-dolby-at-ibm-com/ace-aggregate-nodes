# ace-aggregate-nodes
Example of using ACE Aggregation support with policies

Deploy the projects to a broker with an MQ queue manager associated with it, which should result in the 
creation of two sets of aggregation queues with different prefixes. Note that the broker may need to be
stopped and started to pick up the default policies, depending on what was deployed there originally.

```
C:\Program Files\IBM\ACE\12.0.6.0>curl http://localhost:7080/simpleFlow
{"success":true}
C:\Program Files\IBM\ACE\12.0.6.0>curl http://localhost:7080/topLevelFlow
{"success":true}
C:\Program Files\IBM\ACE\12.0.6.0>curl http://localhost:7080/nonDefaultProject
{"success":true}
```
