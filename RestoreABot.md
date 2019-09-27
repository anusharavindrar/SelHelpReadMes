# Restore a bot

## Restore a bot if accidently deleted the resource on Azure



This has two use scenarios :

1. If the resource is deleted and it has been backed up.
2. If the resource has been deleted and it hasn't been backed up.

## Restore a bot if accidently deleted the files from a file system such as KUDU

If a customer deletes a file from the ABS, they should be able to restore it if they have it backed up. KUDU has file upload so that should work.  

If a customer needs to restore or create a new ABS and they have the code, that is just a matter of deploying the code into the resource. It would be a manual process but easy enough to figure out. 


## Restore a bot using Powershell

## Restore a bot using AZ CLI
