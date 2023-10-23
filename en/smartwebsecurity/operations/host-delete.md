---
title: "Disconnecting a security profile from a virtual host"
description: "Follow this guide to disconnect a security profile from a virtual host."
---

# Disconnecting a security profile from a virtual host

{% list tabs %}

- Management console

   1. In the [management console]({{ link-console-main }}), select the folder where you want to disconnect a [security profile](../concepts/profiles.md) from an [{{ alb-full-name }}](../../application-load-balancer/) [virtual host](../../application-load-balancer/concepts/http-router.md#virtual-host).
   1. In the list of services, select **{{ sws-name }}**.
   1. Select the profile to disconnect from the host.
   1. Go to the **Connected hosts** tab.
   1. Next to the host from which you want to disconnect the profile, click ![options](../../_assets/options.svg) and select ![disconnect](../../_assets/smartwebsecurity/disconnect.svg) **Disconnect from profile**.
   1. Confirm your action.

{% endlist %}