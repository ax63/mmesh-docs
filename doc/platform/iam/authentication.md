---
title: Authentication | mmesh
description: mmesh hybrid cloud integration platform
topic: platform
chapter:
  id: iam
  label: IAM
page:
  name: authentication
  label: Authentication
position: 902
---

You can interact with your mmesh using the webUI or the mmesh CLI. Both apps support user/password authentication.

The mmesh CLI also supports authentication by RSA key.

## User Credentials

You can edit your user credentials and SSH keys using the mmesh webUI or the mmesh CLI.

Browse the [User Settings](/docs/platform/administration/user) section to learn how to manage your mmesh credentials.

## RSA Authentication

The mmesh CLI supports authentication by RSA key.

This is the recommended method of authentication when using the CLI.

It works the same way as SSH does when you enable SSH authentication by public key.

This method can be more convenient, since once enabled, you won't need to enter your credentials manually.

You will need to generate a RSA Key using `ssh-keygen` and put the resulting files in the `${HOME}/.mmesh` directory.

```shell
ssh-keygen
```

Then you need to add the content of the public key (`id_rsa.pub`) to the list of your SSH keys using `mmeshctl user set-ssh-keys` or the mmesh webUI.

```shell
mmeshctl user set-ssh-keys
```

## 2-Factor Authentication

[TBD]
