# ica-clean-profiles-setup
Install the setup files for cleaning student account profiles.

The powershell script will be generated using the cleanprofiles program.

For help in running this script, see the advice comment in opsi-configd

or see the following:

A powershell script will be generated int the c:\temp folder on the client machine and a shortcut will be saved on the Public Desktop.

Execute the shortcut using a privileged domain account. When done, uninstall this procuct to clean up files.

When the shortcut is executed, a cleaning scripts will be saved in the specified folder on the server.

Note: This script expects the WIDECHAR compile option to NOT be set when compileing cleanprofiles.c. I.e, it expects the input to the second stage to be a 8 bit ascii file. If you desire to use the WIDECHAR option, delete the conversion from wide to 8 bit from this script.

 Note: For help depolying the cleaning script using opsi, see:
 
       git@github.com:ICA-IT/ica-clean-profiles.git
       
       
