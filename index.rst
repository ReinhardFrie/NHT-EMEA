.. title:: Nutanix TechEssentials 201 Basic Architecture & Sizing

.. toctree::
  :maxdepth: 2
  :caption: TechEssentials Day 1 - Labs
  :name: _labs1
  :hidden:

  nutanix-basics/ntnxbasics

  nutanix201/nutanix201
  ncc-ui/ncc-ui
  .. foundation-part-1/part1
  .. setup-cluster/setup-cluster
  ncc-cmdl/ncc-cmdl
  .. xray/xray
  .. foundation-part-2/part2
  deployment/deployment
  .. Sizer/sizing-nutanix

.. toctree::
  :maxdepth: 2
  :caption: TechEssentials Day 2 - Nutanix Sizing
  :name: _labs2
  :hidden:

  .. files/files
  .. calm/calm
  .. flow/flow
  .. era/era
  .. karbon/karbon

.. toctree::
  :maxdepth: 2
  :caption: Appendix
  :name: _labsA
  :hidden:

  tools_vms/linux_tools_vm
  tools_vms/windows_tools_vm
  taskman/taskman


.. _getting_started:

Getting Started
===============

.. raw:: html

  <strong><font color="red">Do not start any labs before being told to do so by your
  instructor.</font></strong><br><br>

Welcome to the Nutanix TechEssentials 201 Workshop! Carefully review the **Overview** section of each lab before proceeding with the exercise.

.. note::
  Shown screenshots are there for example purposes! Use **your** information!

.. _cluster_details:

Cluster Access
++++++++++++++

To make sure you use your IP addresses, naming and other information please use the information your instructor has given to you.

.. note::
Write down your IP addresses on a piece of paper to make it a bit easier for yourself...

The Nutanix Hosted Proof of Concept (HPOC) environment can only be accessed via VPN or by connecting to the **NTNX_corp** network.

-------------------------
Lab Access Methods
-------------------------
Parallels VDI
*************

1.Login to https://xld-uswest1.nutanix.com (for PHX) or https://xld-useast1.nutanix.com (for RTP) using your supplied credentials.
2.Select HTML5 (web browser) OR Install the Parallels Client.
3.Select a desktop or application of your choice.

Pulse Secure VPN Client
***********************

1. If client already installed skip to step 5.
2. To download the client, login to https://xlv-uswest1.nutanix.com or https://xlv-useast1.nutanix.com using the supplied user credentials.
3. Download and install client.
4. Logout of the Web UI.
5. Open client and ADD a connection with the following details:.

Type: Policy Secure (UAC) or Connection Server(VPN)
Name: X-Labs - PHX
Server URL: xlv-uswest1.nutanix.com

OR

Type: Policy Secure (UAC) or Connection Server(VPN)
Name: X-Labs - RTP
Server URL: xlv-useast1.nutanix.com

.. GlobalProtect VPN Access
.. ........................

.. Browse to https://gp.nutanix.com.

.. Log in with your OKTA credentials.

.. Download and install the appropriate GlobalProtect agent for your operating system.

.. Launch GlobalProtect and configure **gp.nutanix.com** as the **Portal** address.
