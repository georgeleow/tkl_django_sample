# TKL Django

Getting started fast using [TurnkeyLinux](https://www.turnkeylinux.org/)

## Introduction

Well, have you ever thought how you can quickly turn on and launch a development environment without editing or changing the configuration files on your local machine? 
If yes, this is right for you. I'll make this a quick introduction to [TurnkeyLinux](https://www.turnkeylinux.org/), and I am using the [TKL Django](https://www.turnkeylinux.org/django) appliance as an example.

Before we move on, just to add a bit more on why use a TKL appliance? This really depends on your preferences, the way I see the benefits is: you do not have to edit any local machine's
files or configuration to get started with a development. To do setting in [Virtualbox](https://www.virtualbox.org/) is minimal. 

## Preliminary

This simplified guide assumes you have knowledge and is comfortable using Linux's command lines.

## First steps

First, install Virtualbox in your local machine. Make sure to always use the updated & stable version. Then, download the image in this link [TKL Django](https://www.turnkeylinux.org/django).

## Installation

Read and follow the installation steps by TurnkeyLinux [Appliance Installation Tutorial with VirtualBox](https://www.turnkeylinux.org/docs/installation-appliances-virtualbox-new)

## Configuration

Use the default Bridged network in the VirtualBox settings, it usually works out of the box without changing this part. However, there may be some cases where you will need to change.
Try different network settings value from the dropdown. If all fails, then you will have to tweak changes in the Guest machine. I mean failing to load the homepage with some network error 
such as connection refused. Change in the guest machine to use another port other than `port 80`. 

## It's time to start coding! 

You'll have to mount the project folder in the guest machine so it is accessible from your local machine. This simple introduction does not cover this part. Please check from available
resources on how to mount directories using Linux command lines.
