# firefox 62.0.3

### Date of go-to-build: 2018-10-01

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Iel3zFH9Sc64pTH2zqgEog) Iel3zFH9Sc64pTH2zqgEog
* [push](https://tools.taskcluster.net/push-inspector/#/fXjUYLkoTkKZb_Uv4N2mKQ) fXjUYLkoTkKZb_Uv4N2mKQ
* [ship](https://tools.taskcluster.net/push-inspector/#/QaL2b6JPTta4oPCIQBnBNQ) QaL2b6JPTta4oPCIQBnBNQ
```
export PROMOTE_TASK_ID=Iel3zFH9Sc64pTH2zqgEog
export PUSH_TASK_ID=fXjUYLkoTkKZb_Uv4N2mKQ
export SHIP_TASK_ID=QaL2b6JPTta4oPCIQBnBNQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | mac partner repack failed on downloading a toolchain | True | True |
| jlorenzo  | 2 | [bug 1495714](https://bugzil.la/1495714)        | 502 error, corrupted release blob: "Caught non-fatal exception finding fileUrl for partial update" | True | True |
| asasaki  | 3 | [bug none](https://bugzil.la/none)        | new partner repacks failed signing -- expected | True | True |

