# Ghost SDK
<!-- TOC -->

- [Ghost SDK](#ghost-sdk)
    - [Develop](#develop)
    - [Run](#run)
    - [Test](#test)
    - [Publish](#publish)
    - [Extend GhostSDK/admin-api-schema](#extend-ghostsdkadmin-api-schema)
- [Copyright & License](#copyright--license)

<!-- /TOC -->rn ship --git-remote upstream` to correctly update tags and version commits, when your remote `origin` is set up to a fork of TryGhost/SDK and original repository is set to `upstream`.

## Extend GhostSDK/admin-api-schema

| ファイル      |  | 修正項目                                                                                                                           | 備考          |
|-----------|--|--------------------------------------------------------------------------------------------------------------------------------|-------------|
| post.json |  | "status": {<br/>          "type": "string",<br/>          "enum": ["published", "draft", "scheduled", "sent", "hidden"]<br/>}, | hiddenを追加   |
| post.json |  | "group_id": {<br/>          "type": ["string", "null"],<br/>          "maxLength": 24<br/>},                                   | group_idを追加 |


# Copyright & License

Copyright (c) 2013-2025 Ghost Foundation - Released under the [MIT license](LICENSE).

