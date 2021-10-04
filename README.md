# AI-Data-Collection-for-Minecraft

## Overview
Labeled AI datasets are expensive and time consuming to create. On the other hand, procedurally generated datasets can be created quickly and cheaply. This tutorial will show you how you can generate 10s of thousands of labeled data items every day.

## Minecraft Clients and Servers
While Minecraft provides a vinalla server and client, in order to collect data, we will need a modded server (spigot / paper / etc.) and a modded client (forge). This tutorial will not cover the usage of fabric.

## Client / Server Performance
When collecting data for AI, the client might be running for multiple hours teleporting to tens of thousands of locations. This causes Minecraft to use growing amounts of ram. Methods of addressing this are using tuned jvm paramaters, using a mod to improve memory management, and not using the JRE included with Minecraft. Older versions of Minecraft can also be used to reduce memory usage, although this isn't recommended as not all code in this tutorial is backwards compatible.

### Tuned JVM paramaters
https://www.reddit.com/r/feedthebeast/comments/5jhuk9/modded_mc_and_memory_usage_a_history

