# SvR 2011 iOS port - build repo

Step 1: `ios-sdk` workflow compiles the ReXGlue SDK runtime for iOS arm64.

1. Push this folder to your private repo.
2. Actions -> `ios-sdk` -> Run workflow.
3. Open each job's **Summary** (error list), or download the `logs-*` artifacts, and paste the errors back.

`patches/` are applied on top of the port's own SDK patch, in order.
