---
title: Automation | mmesh
description: mmesh cloud integration platform
topic: platform
chapter:
  id: automation
  label: Automation (Ops)
page:
  name: projects
  label: Projects
position: 702
---

The automation `workflows` are organized in `projects`.

A project is a logical group of workflows where you define common policies to be enforced on the workflows belonging to the project.

## Service Management Features

Currently the options you can configure on a project are the following:

- `Review Required`: [ yes | no ]

  Allows to enforce peer-reviews on the workflows before they can run on the target nodes.

- `Approval Required`: [ yes | no ]

  Useful when the service management policies require approval (from customer or service responsible) on the workflows before they can run on the target nodes.
