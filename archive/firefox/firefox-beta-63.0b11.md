# firefox 63.0b11

### Date of go-to-build: 2018-10-01

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/d8IYPTiNRHmkHjw0IsfIvQ) d8IYPTiNRHmkHjw0IsfIvQ
* [push](https://tools.taskcluster.net/push-inspector/#/JqmGEDGESKaN67BG1FauTA) JqmGEDGESKaN67BG1FauTA
* [ship](https://tools.taskcluster.net/push-inspector/#/XTs7pJYCTHOUMT0UWLdLHA) XTs7pJYCTHOUMT0UWLdLHA
```
export PROMOTE_TASK_ID=d8IYPTiNRHmkHjw0IsfIvQ
export PUSH_TASK_ID=JqmGEDGESKaN67BG1FauTA
export SHIP_TASK_ID=XTs7pJYCTHOUMT0UWLdLHA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1491262](https://bugzil.la/1491262)        | snap push failed | True | False |

