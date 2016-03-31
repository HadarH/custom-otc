---

copyright:
  years: 2016

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}


# Creating a custom toolchain
{: #devops_customotc}
*Last updated: 23 March 2016*

Creating a custom toolchain from the ground up can to meet the needs of your DevOps flow is easy.  This topic will discuss all of the moving parts and how you can customize them to best suit your needs.
{:shortdesc}

A toolchain can easily be deployed from a single Deploy to Bluemix button.  The Deploy to Bluemix button works by referencing a series of configuration files that are set up with specific information about tools and services that should implemented within the toolchain.  These configuration files can easily be created and modified to include only the tools and services you want.

## Getting started
{: #devops_customotc_gettingstarted}

To get started with creating a custom toolchain, you will first need to set up your project

1. In the root of your project, create a directory named `.bluemix`.  This directory will contain all of the configuration files for your project.

The following steps and descriptions will explain the various remaining files and how to customize them.

### toolchain.yml


