---
title: Kubernetes Pods | mmesh
description: mmesh hybrid cloud integration platform
topic: mmesh
chapter:
  id: kubernetes
  label: Kubernetes
page:
  name: kubernetes-pods
  label: Pods
position: 402
---

## Kubernetes Pods Routing

This method connects your Kubernetes Pods as mmesh nodes to a mmesh subnet.

Each Kubernetes Pod becomes a full-featured mmesh node with two-way communication to the mmesh subnet

This way allows you to work with your Kubernetes Pods basically as they were regular VMs or servers from network perspective.

Since the Pods are connected to your mmesh subnet with persistent IPs and DNS names, you can configure mmesh security policies for them the same way you would do for other nodes.

The process injects a mmesh sidecar container into the Kubernetes Pod and does not require any configuration in your application.

## Administration

You can connect your Kubernetes Pods to your mmesh in seconds with the mmesh CLI.

Browse the [Kubernetes Administration](/docs/mmesh/administration/kubernetes) section
to learn how to manage your Kubernetes Pods.
