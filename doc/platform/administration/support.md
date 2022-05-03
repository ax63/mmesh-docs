---
title: Support | mmesh
description: mmesh hybrid cloud integration platform
topic: platform
chapter:
  id: administration
  label: Administration
page:
  name: support
  label: Support
position: 1291
---

mmesh aims to be a simple and enjoyable platform, not only by offering a reliable service to its clients but also by building a premium customer experience.

> See [Customer Service](/docs/platform/support/overview) section to find more information on mmesh Customer Service.

## Operations

You can interact with the mmesh Customer Success Team using the mmesh webUI or the mmesh CLI.

### WebUI: Support

1. In the navigation menu on the left, click `Support` to browse the different options you have to communicate with the mmesh Customer Success Team.

### CLI: Support

#### Open a Chat Session

Open a live-chat session with the mmesh Customer Success Team.

```shell
mmeshctl support chat
```

#### Request Information

Request general information about the platform or the service.

```shell
mmeshctl support info
```

#### Request Technical Support

Request technical support.

```shell
mmeshctl support request
```

#### Submit Feedback

Share your comments and suggestions.

```shell
mmeshctl support feedback
```

#### Report Incident

Report an incident.

```shell
mmeshctl support incident
```

***

#### List your Tickets

List your tickets.

```shell
mmeshctl support ticket list
```

#### Create Ticket

Create a new ticket.

```shell
mmeshctl support ticket create
```

#### Show Ticket

Show all the details of a ticket.

```shell
mmeshctl support ticket show
```

#### Add Comment to Ticket

Add a new comment to an existing ticket:

1. Show the ticket details.
2. Select `Yes` when asked if you want the ticket comments to be shown.
3. Select `Yes` when asked if you want to add a new comment to the ticket.
4. Type the new comment.

```shell
mmeshctl support ticket show

There are comments related to this ticket. Show? (Y/n) => Yes

Add comment to this ticket? (y/N) => Yes

New comment: [Enter two empty lines to finish]
```

#### Close Ticket

Mark a ticket as *Closed*.

```shell
mmeshctl support ticket close
```

#### Delete Ticket

Remove an ticket from the database.

```shell
mmeshctl support ticket delete
```
