# Cirquity Checkpoints

### How To Sync Quickly
##### In versions 0.3.1+ you can sync a fresh chain from 0 much quicker by loading "checkpoints" with your daemon. 

- Download the latest [checkpoints.csv](https://checkpoint.cirquity.com)
    * `curl https://checkpoint.cirquity.com -o checkpoints.csv`
- Place checkpoints.csv in the same folder as your cirquityd daemon
- Run cirquityd with checkpoints added like this: 

Linux, Apple `./cirquityd --load-checkpoints checkpoints.csv`

Windows `cirquityd.exe --load-checkpoints checkpoints.csv`
