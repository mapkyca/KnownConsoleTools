# Development Console Tools for Known

This repo contains a collection of console tools for debugging and developing for Known.

These were written in no particular order for my own use, and might be of use to you when 
developing plugins, patches and sites using Known.

## Requirements

At time of writing you'll need the latest development build of Known, which has Symfony console
application support.

## Usage

Copy or symlink to the directories below so that they appear in ```ConsolePlugins```

## Tools available

* [EntityDump](EntityDump) A tool for outputting the raw contents of an object as identified by UUID, ID or short url
* [EntityList](EntityList) List the UUIDs of the last X entities that match the given search criteria
* [ShowACL](ShowACL) A tool to list the access groups a given user has access to (including those supplied programmatically)
* [TweakEntity](TweakEntity) A tool to tweak field values on a given entity
* [DumpConfig](DumpConfig) Dump the current running config
* [ListUsers](ListUsers) Quickly list system users, or optional admin users


## Warning

I wouldn't recommend having these in place on a live system, as that would likely pose a security risk.

These tools, for example, let you dump entity data etc.

# See

* Author: Marcus Povey http://www.marcus-povey.co.uk

