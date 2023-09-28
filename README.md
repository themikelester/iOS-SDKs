This is a "filtered" version of the the original iOS-SDKs repo. This was done to keep the size of the repo small, for easy inclusion in projects which just require a few headers. 
The filtering was done using the [git-filter-repo](https://github.com/newren/git-filter-repo/) script, with the following command:
`git-filter-repo --path iPhoneOS17.0.sdk/usr/include/simd/`

To update to a newer SDK version, sync this repo with the original, re-run the filtering command, and then force push.
