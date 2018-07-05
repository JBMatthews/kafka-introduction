## Installing Nano

### In this Lab

**Objective:** Learn more about this particular techonology.

**Successful Outcome:** Simply following along with the step written below and complete each before moving to the next.

**Lab Files:** `xx`

----

### Steps

Vim is the default editor on Linux, but you may prefer a full-screen GUI. Try nano.

<img src="https://user-images.githubusercontent.com/558905/40613898-7a6c70d6-624e-11e8-9178-7bde851ac7bd.png" align="left" width="30" height="30" title="ToDo Logo"/>
<h4>Installing Nano via Terminal</h4>

```
yum install nano
```

Output:
```
Loaded plugins: fastestmirror
HDP-2.6-repo-1                                                                                                    | 2.9 kB  00:00:00
HDP-UTILS-1.1.0.22-repo-1                                                                                         | 2.9 kB  00:00:00
ambari-2.6.1.5                                                                                                    | 2.9 kB  00:00:00
base                                                                                                              | 3.6 kB  00:00:00
epel/x86_64/metalink                                                                                              |  17 kB  00:00:00
epel                                                                                                              | 3.2 kB  00:00:00
extras                                                                                                            | 3.4 kB  00:00:00
mysql-connectors-community                                                                                        | 2.5 kB  00:00:00
mysql-tools-community                                                                                             | 2.5 kB  00:00:00
mysql56-community                                                                                                 | 2.5 kB  00:00:00
updates                                                                                                           | 3.4 kB  00:00:00
(1/2): epel/x86_64/updateinfo                                                                                     | 932 kB  00:00:00
(2/2): epel/x86_64/primary                                                                                        | 3.5 MB  00:00:00
Loading mirror speeds from cached hostfile
 * epel: s3-mirror-us-west-2.fedoraproject.org
epel                                                                                                                         12584/12584
Resolving Dependencies
--> Running transaction check
---> Package nano.x86_64 0:2.3.1-10.el7 will be installed
--> Finished Dependency Resolution

Dependencies Resolved

=========================================================================================================================================
 Package                       Arch                            Version                               Repository                     Size
=========================================================================================================================================
Installing:
 nano                          x86_64                          2.3.1-10.el7                          base                          440 k

Transaction Summary
=========================================================================================================================================
Install  1 Package

Total download size: 440 k
Installed size: 1.6 M
Is this ok [y/d/N]: y
Downloading packages:
nano-2.3.1-10.el7.x86_64.rpm                                                                                      | 440 kB  00:00:00
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : nano-2.3.1-10.el7.x86_64                                                                                              1/1
  Verifying  : nano-2.3.1-10.el7.x86_64                                                                                              1/1

Installed:
  nano.x86_64 0:2.3.1-10.el7

Complete!
```

Now you can edit files on Linux a little more naturally.

A couple of cheatsheets for Nano:

1. [Cheatography](https://www.cheatography.com/tag/nano/)
2. [Cheat-Sheets](http://www.cheat-sheets.org/saved-copy/Nano_Cheat_Sheet.pdf)
3. [How-To](https://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/)



### Results

You are finished! Great job!