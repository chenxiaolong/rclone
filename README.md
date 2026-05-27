**2026-05-26**: As of https://github.com/chenxiaolong/RSAF/pull/290, RSAF no longer requires using this fork. It now uses upstream rclone.

This repo contains a fork of rclone formerly used by [RSAF](https://github.com/chenxiaolong/RSAF). The only addition is the ability to hook into HTTP requests so that RSAF can update the set of trusted CA certificates in response to runtime changes to Android's trust store.

The commits are published as part of the `<version>-rsaf.<revision>` tags.
