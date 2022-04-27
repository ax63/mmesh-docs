---
title: "IAM: ACLs | mmesh"
description: mmesh hybrid cloud integration platform
topic: platform
chapter:
  id: administration
  label: Administration
page:
  name: iam-acls
  label: "IAM: ACLs"
position: 1287
---

An `ACL` controls the access to your nodes.

An ACL is defined with the set of nodes that the user will have access.

The IAM subsystem of mmesh allows to manage the ACLs.

> See [Identity and Access Management](/docs/platform/iam/authorization#access-control-lists-acls) section to find more information about the mmesh authorization subsystem.

## Attributes

The following table includes the attributes that define a mmesh `ACL`:

| Name     | Type     | Default | Editable<sup>*</sup> | Description |
| :------- | :------: | :-----: | :------------------: | :---------- |
| `acl-id` | `string` |         | no  | ACL identifier |
| `nodes`  | `array`  |         | yes | list of node identifiers |

<table-note>
The parameter can be modified once the entity is created.
</table-note>

## Operations

You can manage the account ACLs using the mmesh webUI or the mmesh CLI.

### WebUI: IAM | ACLs

1. In the navigation menu on the left, click `Account` to expand the menu item, then click `IAM`.

### CLI: IAM | ACLs

#### List ACLs

List all the account ACLs.

```shell
mmeshctl iam acl list
```

#### Create ACL

Create a new ACL.

```shell
mmeshctl iam acl set
```

#### Show ACL

Show all the details of an ACL.

```shell
mmeshctl iam acl show
```

#### Update ACL

Update an ACL.

The following parameters are *editable*:

- `nodes`

```shell
mmeshctl iam acl set
```

#### Delete ACL

Delete an ACL.

```shell
mmeshctl iam acl delete
```
