# PWPush Generator

A Powershell GUI application using the PWpush.com API so that anyone can generate secure passwords from their desktop.

## How to use
PowerShell.exe -ExecutionPolicy Bypass -File .\PWPush_Generator.ps1

## Notes
I added $Passphrase to the function written by [pgarm](https://github.com/pgarm/pwposh/tree/main) so Passphrases could be used.
The only option not available so far is customization of passwords. It uses all valid alpabetic characters with these special characters. ('!', '@', '#', '%', '^', '&', '*')

## Thanks

Thanks go to [Peter Giacomo Lombardo](https://github.com/pglombardo), creator of PWPush and [pgarm](https://github.com/pgarm/pwposh/tree/main) for the two functions that use the API.