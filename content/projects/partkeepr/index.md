---
title: "parts inventory with Partkeepr"
date: 2019-10-04T19:44:57+02:00
tags: [Parts, Inventory, Docker, Partkeepr, compose]
description: Where is the teleportation gate? Look in Partkeepr!
thumbnail: partkeepr-logo-only.jpeg
---

{{< figureCupper img="partkeepr-logo.png" command="Resize" options="700x" caption="" >}}

As we have a nice hackerspace with plenty of room, we also have quite some equipment, parts, tools and raw materials.

In order to find a particular item, we decided to setup a partkeepr instance. 

The project is on github : <https://github.com/ko-lab/partkeepr>

This particular instance is set up in a docker container. It is started up with docker compose together with a database
container. This makes it easy to reinstall from a reference when needed.

{{< figureCupper img="partkeepr-on-pc.jpg" command="Resize" options="700x" caption="Our local Partkeepr PC" >}}
{{< figureCupper img="partkeepr-overview.png" command="Resize" options="700x" >}}
{{< figureCupper img="partkeepr-add-part" command="Resize" options="700x" >}}
