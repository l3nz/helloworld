# Getting started

## Installing the module


In order to have a local repo working, you need to link it under /var/www/html/admin/modules

So you install a fresh FreePBX 13 system, log in as root and do:

     cd /var/www/html/admin/modules
     git clone https://github.com/l3nz/helloworld
     fwconsole chown

At this point, you should see the available module:

    [root@localhost modules]# fwconsole ma list | grep hello
    | helloworld           |               | Not Installed (Locally available)         |

And you van install it as:

     [root@localhost modules]# fwconsole ma install helloworld
     Creating the database table
     Generating CSS...Done
     Updating Hooks...Done
     Module helloworld successfully installed
     Setting Permissions...
     246/246 [============================] 100%
     Finished setting permissions


At this point you should be able to see it in the GUI, under .....

## Tweaking the module

TBD






## When something goes wrong

logs are to be found in: ....

## See also

Uniformity guidelines for FreePBX 13: ....

The original project: https://github.com/jfinstrom/helloworld

Misc snippets: https://github.com/jfinstrom/FreePBX-gists











