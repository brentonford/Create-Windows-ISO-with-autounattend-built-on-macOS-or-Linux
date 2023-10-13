Checks if the WinPE plain BIOS ISO `{automationWorkerBaseDirectory}/winpe_plain_bios.iso` exists.

If it does not, prints a message to ask user to run the WinPE BIOS ISO creation blueprint `Create Windows PE (WinPE) Plain ISO on macOS or Linux Worker`.

Only applies to BIOS kickstarts so if any of these parameters are set the string 'true':

1. isWin10Bios
2. isWinServerBios