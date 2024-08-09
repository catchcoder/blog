---
title: "Make USB flash drive Read-Only"
date: 07-08-2024
---

## Requirements:
 - USB Flash Drive
 - Windows 10/11
   
## Instructions to make a USB flash drive Read-Only.

Start by running a command prompt (as administrator)

1. Lunch CMD to start a Command Prompt
2. Type "diskpart"
1. Type "list disk" and take note of the number for your flash drive
1. Type "select disk [USB drive number]" e.g. "select disk 3"
1. Type "attributes disk" to display the settings (see images below)
1. Type "attributes disk set readonly"
1. Type "exit", all done you can now test the flash drive to see if you can add or edit the contents of it.

## Instructions to make USB Flash Drive Writable

1. Lunch CMD to start a Command Prompt
2. Type "diskpart"
1. Type "list disk" and take note of the number for your flash drive
1. Type "select disk [USB drive number]" e.g. "select disk 3"
1. Type "attributes disk" to display the settings (see images below)
1. type "attributes disk clear readonly" then "exit"

Note: This method has been tested using FAT32, exFAT and NTFS file systems.

## Images from DISKPART

![DISKPART command displaying the Read-Only attribute set to No](https://github.com/catchcoder/blog/blob/8bcfb76d9ea63bc79af5b5fc24d2554e6d697c15/_images/diskpart-readonly-cleared.PNG?raw=true)

![DISKPART command displaying the Read-Only attribute set to Yes](https://github.com/catchcoder/blog/blob/8bcfb76d9ea63bc79af5b5fc24d2554e6d697c15/_images/diskpart-readonly-set.PNG?raw=true)
