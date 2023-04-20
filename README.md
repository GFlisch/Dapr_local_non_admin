# Dapr_local_non_admin
Script to install Dapr on a non admin dev pc.


In a terminal window with Powershell execute the command:

.\install-dapr.ps1 v1.10.5

This will copy the dapr cli and runtime. Install it on the default c:\Prj\Dapr folder.

The local environment will be updated and you will be able to run the dapr cli via the "ldapr" command.

> Note.
> To be able to do this in the current terminal window, please shut down terminal and restart it.

If you want to install in another folder than the standard one => execute the following command:

.\install-dapr.ps1 v1.0.10  "C:\Other folder"

