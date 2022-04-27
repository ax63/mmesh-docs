---
title: "IAM: Security Groups | mmesh"
description: mmesh hybrid cloud integration platform
topic: mmesh
chapter:
  id: administration
  label: Administration
page:
  name: iam-security-groups
  label: "IAM: Security Groups"
position: 1285
---

A `security group` controls the access to your mmesh tenants.

A security group is defined with the list of tenants that the user will have access.

The IAM subsystem of mmesh allows to manage the security groups.

> See [Identity and Access Management](/docs/mmesh/iam/authorization#security-groups) section to find more information about the mmesh authorization subsystem.

## Attributes

The following table includes the attributes that define a mmesh `security group`:

| Name          | Type      | Default | Editable<sup>*</sup> | Description |
| :------------ | :-------: | :-----: | :------------------: | :---------- |
| `security-group-id` | `string` |         | no  | security group identifier |
| `tenants`           | `array`  |         | yes | list of tenants |

<table-note>
The parameter can be modified once the entity is created.
</table-note>

## Operations

You can manage the account security groups using the mmesh webUI or the mmesh CLI.

### WebUI: IAM | Security Groups

1. In the navigation menu on the left, click `Account` to expand the menu item, then click `IAM`.

### CLI: IAM | Security Groups

#### List Security Groups

List all the account security groups.

```shell
mmeshctl iam security-group list
```

#### Create Security Group

Create a new security group.

```shell
mmeshctl iam security-group set
```

#### Show Security Group

Show all the details of a security group.

```shell
mmeshctl iam security-group show
```

#### Update Security Group

Update a security group.

The following parameters are *editable*:

- `tenants`

```shell
mmeshctl iam security-group set
```

#### Delete Security Group

Delete a security group.

```shell
mmeshctl iam security-group delete
```
