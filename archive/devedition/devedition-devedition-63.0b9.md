# devedition 63.0b9

### Date of go-to-build: 2018-09-24

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/EvKRi0dUQEGWuI6ICk8sBA) EvKRi0dUQEGWuI6ICk8sBA
* [push](https://tools.taskcluster.net/push-inspector/#/Rawi4CqbRKyfSbhfRmV2fA) Rawi4CqbRKyfSbhfRmV2fA
* [ship](https://tools.taskcluster.net/push-inspector/#/RP0JVwfITYa_oQP4bTWaog) RP0JVwfITYa_oQP4bTWaog
```
export PROMOTE_TASK_ID=EvKRi0dUQEGWuI6ICk8sBA
export PUSH_TASK_ID=Rawi4CqbRKyfSbhfRmV2fA
export SHIP_TASK_ID=RP0JVwfITYa_oQP4bTWaog
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug none](https://bugzil.la/none)        | Update verify bustage from [tools cleanup](https://hg.mozilla.org/build/tools/rev/d5289f1ceaaa); fixed by re-adding retry.py and unix_util.py. | True | False |

