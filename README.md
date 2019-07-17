# WiX.Tutorial

Sample project to get familiarized with [WiX Toolset](https://wixtoolset.org/).

## See
https://www.firegiant.com/wix/tutorial/

## How to's
First download WiX binaries from the official [download page](https://wixtoolset.org/releases/) and copy them to WiX folder.
Please note that this repository was tested using WiX 3.11.

To remove the installed MSI go to 'Programs and Features' or run
`msiexec /x SampleFirst.msi`

If you want to see what's going on during the installation you can run installation via 
`msiexec /i SampleFirst.msi /l*v SampleFirst.log`