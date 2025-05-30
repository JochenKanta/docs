---
title: "Wiring Your Supermicro A+ ASG-1014S-ACR12N4H Nodes"
summary: "This section explains how to wire the out-of-band management (IPMI) port, 25 Gbps or 100 Gbps ports, and power on Supermicro 1014S nodes."
permalink: /hardware-guide/supermicro-a-plus-asg-1014s-acr12n4h/wiring-nodes.html
redirect_from:
  - /hardware/supermicro-a-plus-asg-1014s-acr12n4h/wiring-nodes.html
sidebar: hardware_guide_sidebar
keywords: out-of-band management, out of band management, IPMI, DHCP, network, networking, LAN, ipmitool, 100 Gbps, Ethernet, power, Supermicro 1014S, ACR12N4H
---

{% include note.html content="The two Ethernet ports on the back of your node (to the right of the USB ports) are unused." %}

{% capture alt_tag %}Back Diagram of the {{site.sm1014sLong}} Node{% endcapture %}
{% include image.html alt=alt_tag file="supermicro-1014s-back-diagram.png" url="/hardware-guide/supermicro-a-plus-asg-1014s-acr12n4h/images/supermicro-1014s-back-diagram.png" %}

{% include content-reuse/platform-agnostic-unified-networking-wiring-25-100-gbps.md %}
