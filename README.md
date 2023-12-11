# PWPush Generator
<p align="center">
  <img src="https://github.com/Tachaeon/PWPush-Generator/blob/main/images/screengrab.png" />
</p>

I have created a GUI application from Powershell using the PWpush.com API so that anyone can generate secure passwords from their desktop.

## How to use
PowerShell.exe -ExecutionPolicy Bypass -File .\PWPush_Generator.ps1

## Notes
- I added $Passphrase to the function written by [pgarm](https://github.com/pgarm/pwposh/tree/main) so Passphrases could be used.
- The only option not available so far is customization of passwords. It uses all valid alphabetic characters with these special characters. ('!', '@', '#', '%', '^', '&', '*')
- The 30sec timer that clears the fields is a little added security so you don't accidentally send the same password or PWPush URL to different people.

## Thanks

Thanks go to [Peter Giacomo Lombardo](https://github.com/pglombardo), creator of PWPush and [pgarm](https://github.com/pgarm/pwposh/tree/main) for the two functions that use the API.
