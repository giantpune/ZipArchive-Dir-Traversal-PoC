# ZipArchive 2.1.4 dir traversal 1172-Day

## How to test
* run: `./poc.sh`

## Root cause
* symlink in zip

## Additional info
This issue has been reported, but ignored by the developers.
* https://github.com/ZipArchive/ZipArchive/pull/454
* https://zipperdown.org/
![ZipperDown2](ZipperDown2.png)

This issue was previously demonstrated by Nowsecure in 2015 with a PoC and full write up.
* https://github.com/nowsecure/android-rce-multidex-and-zip-files/blob/master/secondary_dex_remote_code.py#L42-L53
* https://www.nowsecure.com/blog/2015/06/15/a-pattern-for-remote-code-execution-using-arbitrary-file-writes-and-multidex-applications/
* https://www.nowsecure.com/blog/2018/05/18/adventures-remote-code-execution-zip-file-vulns-samsung-vungle-zipperdown/
