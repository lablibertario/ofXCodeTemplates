XCode 3.0+ templates for openFrameworks Applications for Desktop and iPhone .

03/06/2009
Mehmet Akten
www.memo.tv

== INSTALLATION ==
just unzip and place the openFrameworks folder in ONE of the following folders:
/Library/Application Support/Developer/3.0/Xcode/Project Templates
/Library/Application Support/Developer/Shared/Xcode/Project Templates
~/Library/Application Support/Developer/3.0/Xcode/Project Templates
~/Library/Application Support/Developer/Shared/Xcode/Project Templates

If any of the above paths don't exist, you can just go ahead and create the relevant folders.

Tip. I have the templates in the folder: ~/Library/Application Support/Developer/Shared/Xcode/Project Templates so when I sync the home folders of multiple macs (using ChronoSync) the templates get updated and stay in sync between multiple computers.

== USAGE ==

1. Launch XCode, and from file menu select New Project (SHIFT + CMD + N).
From the sidebar on the left select the openFrameworks group (under USER TEMPLATES), and then select between:
- Desktop openFrameworks App (to develop for OSX and desktop macs) or
- iPhone openFrameworks App (to develop for iPhone)

2. Choose a name and location for the project.
A folder will be created with the name you choose, also the executable will have the same name and so will the xcode project.

Note the location HAS to be a subfolder of the apps in the related openframeworks working directory.

I.e. If you are creating a desktop application, you need to choose the location:
<folder_where_openframeworks_macosx_is> / apps / <some_folder>

This will create the folder below and place all files in there:
<folder_where_openframeworks_macosx_is> / apps / <some_folder> / <project_name>
e.g.
/Users/Memo/Documents/openFrameworks_mac/apps/Memo Stuff/Killer App 3

Likewise if you are creating an iphone application, you need to choose the location:
<folder_where_openframeworks_iphone_is> / apps / <some_folder>

This will create the folder below and place all files in there:
<folder_where_openframeworks_iphone_is> / apps / <some_folder> / <project_name>
e.g.
/Users/Memo/Documents/openFrameworks_iphone/apps/Memo Stuff/Killer App 4

DISTRIBUTE FREELY AND ENJOY!

IF YOU MAKE ANY MODS, FIND ANY BUGS OR IMPROVEMENTS PLEASE LEMME KNOW! 