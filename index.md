---
layout: page
title: Windows Azure Contrib
tagline: Community contributions for Windows Azure
---
{% include JB/setup %}

## About

This GitHub organisation aims to bring together a collection of [Open Source Software projects](https://github.com/orgs/WindowsAzure-Contrib) related to Microsoft Windows Azure.

The organisation is guided by a [small team](https://github.com/orgs/WindowsAzure-Contrib/teams/owners) of open source contributors.
    
## Wider Community

As well as the projects hosted here, there are a number of projects available in the wider community.

If your project is not listed here, please fork [this repo](https://github.com/WindowsAzure-Contrib/WindowsAzure-Contrib.github.io) and add it!

### Windows Azure Web Sites

* __[countersoft/Azure](https://github.com/countersoft/Azure)__ Run Gemini on Windows Azure Web Sites

### Cloud Services

* __[AzureRunMe](https://github.com/RobBlackwell/AzureRunMe)__ Runs third party technologies on Windows Azure Cloud Services
* __[AzurePluginLibrary](http://richorama.github.io/AzurePluginLibrary/)__ A library of plugins for the Windows Azure Cloud Services SDK
* __[AzureStickySessions](https://github.com/WindowsAzure-Contrib/AzureStickySessions)__ An Azure role that configures ARR as a sticky session load balancer
* __[mongo-azure](https://github.com/mongodb/mongo-azure)__ MongoDB on Azure Worker Roles
* __[Two10.Azure.SelfDestruct](https://github.com/richorama/Two10.Azure.SelfDestruct)__ A library allowing an Azure WebRole/WorkerRole to delete itself 

### IaaS

* __[WindowsAzureDiskResizer](https://github.com/WindowsAzure-Contrib/WindowsAzureDiskResizer)__ Resizes a Windows Azure virtual disk directly in blob storage

### Media Services

* __[MediaServicesCommandLineTools](https://github.com/RobBlackwell/MediaServicesCommandLineTools)__ Tools and sample code for Windows Azure Media Services

### Storage

* __[azuretablebackup](https://github.com/richorama/azuretablebackup)__ A command line utility to backup and restore Windows Azure Table Storage

### SQL Database

* __[SQLDatabaseBackup](https://github.com/richorama/SQLDatabaseBackup)__ A command line tool for backing up a Windows Azure SQL Database to Blob Storage, by making a copy of the database

### .NET / Mono

* __[https://github.com/WindowsAzure-Contrib/AzureDirectory](https://github.com/WindowsAzure-Contrib/AzureDirectory)__ A Lucene Directory Provider for Windows Azure Blob Storage
* __[https://github.com/smarx/WazStorageExtensions](https://github.com/smarx/WazStorageExtensions)__ Useful extension methods for Windows Azure storage operations that aren't covered by the .NET client library
* __[azure-sdk-for-mono](https://github.com/richorama/azure-sdk-for-mono)__ Fork of the Windows Azure SDK for .NET repo, modified to compile for mono

### .NET Micro Framework 

* __[netmfazurestorage](https://github.com/WindowsAzure-Contrib/netmfazurestorage)__ A unified Windows Azure Storage SDK for .net Microframework

### Node.js

* __[azure-scripty](https://github.com/WindowsAzure-Contrib/azure-scripty)__ Library for scripting out the azure-cli
* __[azure-node-tuneup](https://github.com/WindowsAzure-Contrib/azure-node-tuneup)__ give your node app in Windows Azure web sites a tuneup
* __[node-azure-workshop](https://github.com/WindowsAzure-Contrib/node-azure-workshop)__ Node.js / Azure workshop materials
* __[node-bluesky](https://github.com/pofallon/node-bluesky)__ A lightweight, simplified node.js library for accessing Windows Azure
* __[connect-bluesky](https://github.com/pofallon/connect-bluesky)__ A Windows Azure table storage session store for the node.js Connect/Express web framework


### Java

* __[jclouds](https://github.com/jclouds/jclouds)__ Provisioning and control of cloud resources, including blobstore and compute, from Java and Clojure.

### PHP

* __[azure-session-handler](https://github.com/WindowsAzure-Contrib/azure-session-handler)__ Use Windows Azure Table Storage as a session handler for PHP applications

### Erlang

* __[winazureerl](https://github.com/sriramk/winazureerl)__ Erlang bindings for Windows Azure

### Perl

* __[waz-storage-perl](https://github.com/smarx/waz-storage-perl)__ Small library for working with Windows Azure storage from Perl

### Common Lisp

* __[cl-azure](https://github.com/robblackwell/cl-azure)__ A Windows Azure cloud services library for Common Lisp


## Updates

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


