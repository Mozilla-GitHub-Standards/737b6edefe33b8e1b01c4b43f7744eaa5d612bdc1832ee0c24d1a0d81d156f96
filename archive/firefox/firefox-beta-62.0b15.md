# firefox 62.0b15

### Date of go-to-build: 2018-08-06

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/DmKeYx0FSCCAFwAbJA3HBg) DmKeYx0FSCCAFwAbJA3HBg
* [push](https://tools.taskcluster.net/push-inspector/#/K8-VqBReSBKI3vWTZZvZeA) K8-VqBReSBKI3vWTZZvZeA
* [ship](https://tools.taskcluster.net/push-inspector/#/V2UI5WgWTMG2BkoxfGVMzw) V2UI5WgWTMG2BkoxfGVMzw
```
export PROMOTE_TASK_ID=DmKeYx0FSCCAFwAbJA3HBg
export PUSH_TASK_ID=K8-VqBReSBKI3vWTZZvZeA
export SHIP_TASK_ID=V2UI5WgWTMG2BkoxfGVMzw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Vopv3qRQQTuhL1INPnfAKA) Vopv3qRQQTuhL1INPnfAKA
```
export PROMOTE_TASK_ID=Vopv3qRQQTuhL1INPnfAKA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1476065](https://bugzil.la/1476065)        | Github API outage caused decision task lookup of partner data to fail | True | True |

