<!-- release-migration-20261023 -->
## Release distribution moved to the project repository

[Project releases](https://github.com/MisakaPiano/CCB-Studio-Suite/releases) are the canonical download location. All current packages are synthetic-workspace prerelease tests, not daily-use releases.

The former distribution repository is retained for compatibility. Historical 100–103 assets are unchanged. Long-term-channel 102/103 can update through the old address to bridge 104; installed 104 then checks the project repository. The temporary 100/101 trust channel remains historical and is not silently replaced.

Both long-term channels keep snapshot/timestamp renewal. The compatibility channel can remain pinned to bridge 104; its targets metadata still requires offline renewal before expiry. TUF signatures are not Windows Authenticode.

The following text is historical project/channel information; the migration status above takes precedence for distribution.

---

# CCB Studio Suite update channel validation

This repository is being prepared for update-channel validation. No daily-use release is available yet.

The initial validation uses synthetic workspaces and disposable test trust. Test metadata and package versions must not be treated as a stable update channel. Do not use test packages with personal workspaces.

The application source repository and its visibility are managed separately. This repository contains distribution materials only; no personal pictures, prompts, account credentials or private signing keys belong here.

Current status: real GitHub download, application restart and end-to-end data verification are not yet confirmed. Formal release signing, maintenance and user acceptance remain pending.
