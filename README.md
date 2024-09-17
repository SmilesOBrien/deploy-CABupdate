# deploy-CABupdate
A script for downloading / installing a Windows Update via CAB file from the update catalogue.

Designed to be used for mass deployments via SmartDeploy, but could be used with any other solution that allows you to run PowerShell scripts against remote comptuers, or manually via a USB drive and PowerShell.

# Why does this exist?
A Realtek update via Windows Updates caused the front-facing cameras to go into "Disco Rave" mode, glitching out with colored screens. This happened on every ASUS Expertbook computer we had. I verified that this was a software issue, and that updating to the most recent Realtek driver via the update catalogue resolved the issue. I then wrote a script that I could push out via our imaging and application management solution (SmartDeploy). I've made that script generic for inclusion here.

# How To Use
1. Update the variables and file paths in the script at specified
2. Run the script manually, or with your preferred deployment solution.
