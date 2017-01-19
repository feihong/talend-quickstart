# Feihong's Talend Open Studio Quickstart

## Installation

1. Make sure you have Java 8 installed.
1. Download Talend Open Studio for Data Integration from [SourceForge](https://sourceforge.net/projects/talend-studio/files/latest/download) or the [Talend website](http://www.talend.com/download/talend-open-studio/#t4). Don't click on the link that reads "Try Now", that leads to a trial of the paid version. Only the link that reads "Download Free Tool" leads to the free version.
1. Once you've downloaded the zip file, `unzip` it and move the folder to `~/Applications`.
1. In your bash file, add some code that looks like this:

   ```
   export TALEND_DIR="$HOME/Applications/TOS_DI-20161026_1219-V6.3.0"
   alias talend="cd $TALEND_DIR/TOS_DI-macosx-cocoa.app/Contents/MacOS; ./TOS_DI-macosx-cocoa"
   ```
1. Source your bash file.
1. Start Talend Open Studio by running `talend` at the command line.
1. Create a new project, then proceed to download the required packages. 

## Running

You can start Talend Open Studio by running `talend` at the command line.

## Documentation

Download the [User Guide](https://info.talend.com/rs/talend/images/UG_EN_DI_TOSDI.pdf) as a PDF file.

## Sources

[Mac Install : unable to locate its companion shared library](https://talendforge.org/forum/viewtopic.php?id=14844)
