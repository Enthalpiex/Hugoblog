---
title: New Encryption Plugin
author: Entropiex
description: 
date: 2025-03-05
image: first.png
toc: false
categories:
  - Plugin & Software
math: false
tags:
---
This is an Obsidian plugin development plan.

Apparently, Meld Encrypt has a very bad interactive design. Every time a user selects a file in the file browser, the file preview function will show an overview of the file content. At this time, Meld Encrypt will automatically pop up a password box, which must be closed manually to continue looking for files. This is very bad - most of the time, the mouse just hovers for a while to trigger this troublesome password input box. 

In addition, Meld Encrypt is very slow when switching during decryption, and occasionally undecrypted garbled characters will appear, which threatens the smooth Obsidian experience.

For this reason, I decided to develop a new lightweight plugin that has all the functions of Meld Encrypt, but is faster, safer and more stable. 

The new encryption plugin will also introduce asymmetric encryption technology. Perhaps elliptic curves are a good choice.