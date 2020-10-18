# INC 001

##Name: </br>

CpuLoad

##Description:

This alert would fire when the free memory is less than the configured theshold.


## Steps:
1. Identiy the process which is killing memory
```bash
$ free -m
```
Then check cpu and process id
```bash
$ top
```

2. Try to kill that unessaccary process
```bash
$ docker rm -f <docker cont. id>
```


## Side effects

NA


## Impact

* you may loose control over the instance


