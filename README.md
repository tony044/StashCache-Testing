# StashCache-Testing
Testing StashCache at the Computation Institute

Submit and Shell scripts are based off Bala's previous testing scripts. 

.out file includes the closest calculated server, total file size transferred, and error.

.err file includes a more detailed error report, as well as debugging info, and time used for wget and stashcp

Future plans:

-Running 1k+ jobs which are set to start at a time between 0 seconds and 1 hour. This would test whether servers are being overloaded by being hit with all jobs at once, thus putting jobs in a queue possibly leading to timeouts.

-Directing jobs at particular servers

-This: https://github.com/opensciencegrid/StashCache/blob/master/explanation.md#known-issues-and-concerns


Testing summary: https://docs.google.com/presentation/d/1tV3JKAIO0ReSeht8ULtCMqVuw_2laTEp4-iSPJjD8UA/edit?usp=sharing
