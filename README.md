CALLERID.COM
iOS Sample Application
---------------------
spenland@callerid.com
-------------------------------------------------------------------------------

iOS Development
 - This app will uses the 'CocoaAsyncSocket' libraries to make UDP coding easier.
 - This app will aslo be using SQLite which will mean including the FMDB wrapper
   for Objective-C.
 - App targets iPhone 5s. 

-------------------------------------------------------------------------------
Refer to this repo's source code for example application.
-------------------------------------------------------------------------------




-------------------------------------------------------------------------------
To begin your own iOS project do the following:
-------------------------------------------------------------------------------

1- Install cocoaPods:
	https://cocoapods.org
	
	Terminal install:
	sudo gem install cocoapods

2- Create a project using XCode.

3- Create/initalize podfile to include:
	use_frameworks!
	pod 'CocoaAsyncSocket'
	pod 'FMDB'
	
4- In terminal CD to your project directory
    Run 'pod install' to add dependencies to your project
	
	       ***After using 'pod install'***
	Remember to open your project from now on using the
	'workspace' file instead of project file.
	***************************************************
	
5- Refer to this repo's source example for help.