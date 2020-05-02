# A Quick Guide to Set Up Tezos Baker on Vultr

\* *Updated: May 2nd, 2020*

##### Table of Contents
[I. Deploy a Clould Instance (Server)](#deployAnInstance)\
[II. Install Tezos Blockchain](#installTezosBlockchain)\
[III. Start Baking Process](#startBakingProcess)

## I. Deploy a Cloud Instance (Server)

<a name="deployAnInstance"></a>

If you have used Vultr to run a server before, skip to **Step 4**.

**Step 1: Go to https://www.vultr.com/ to register an account, and update billing information**

**Step 2: Login and go to https://my.vultr.com/deploy/ to deploy a cloud instance**

* Choose Server: **Cloud Compute** (general purpose server)
* Server Location: **Singapore** (closest to where I live to get stable remote access)

<img src="setup-tezos-baker-on-vultr-images/deploy-a-vultr-instance-choose-server-and-location.png" height="500">

* Server Type: **Ubuntu 18.04 x64** (a popular OS)
* Server Size: **80 GB SSD, 2 CPU, 4096MB RAM** (best deal for baking purpose)

<img src="setup-tezos-baker-on-vultr-images/deploy-a-vultr-instance-choose-server-type-and-size.png" height="500">

