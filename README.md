# EPCEncoderOSX
Build the EPCEncoder lib and framework for OSX, includes Converter.

Note: most of this project leverages this great tutorial to create a framework:

http://www.raywenderlich.com/65964/create-a-framework-for-ios

For this version, I only got the framework to work not the static library.  This framework is only used for 
GeniTag on the MacOS

The framework is in the build subdirectory.  This version also build the framework with every build, so the
post run scripts are a little different than the tutorial linked above.

TPM - 11/18/15

With the release of XCode 7 for iOS 9, you have to choose your platform.  Before you could use the same framework
for both iOS and OSX.  No longer.  I've split this into two now, one framework for iOS and another for OSX.