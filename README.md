# trainPlanner
Quick python command line tool that queries the Darwin National Rail API for train times between two stations.

Requires a .envrc file with a valid apiKey set as an environmental variable.

Example usage:

`python3 train --destination stl --departing pad --operator "TFL Rail"`                                                                                                   

```
Request generated at: 13:29:59
--------------------------
Trains departing pad and arriving at stl
Scheduled: 13:33 Estimated: On time Platform: 12
Scheduled: 13:47 Estimated: On time Platform: None
Scheduled: 14:02 Estimated: On time Platform: None
Scheduled: 14:17 Estimated: On time Platform: None
Scheduled: 14:32 Estimated: On time Platform: None
Scheduled: 14:47 Estimated: On time Platform: None
Scheduled: 15:03 Estimated: On time Platform: None
```
