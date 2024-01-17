<!---
Mahyap/Mahyap is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Last login: Tue Jan 16 23:59:00 on ttys001
stmgroupteknoloji@STM-MacBook-Pro ~ % pwd  
/Users/stmgroupteknoloji
stmgroupteknoloji@STM-MacBook-Pro ~ % cd..
zsh: command not found: cd..
stmgroupteknoloji@STM-MacBook-Pro ~ % cd ..
stmgroupteknoloji@STM-MacBook-Pro /Users % cd ..
stmgroupteknoloji@STM-MacBook-Pro / % cd Applications/VMware\ Fusion.app/Contents/Library/VMware\ 
cd: no such file or directory: Applications/VMware Fusion.app/Contents/Library/VMware 
stmgroupteknoloji@STM-MacBook-Pro / % cd Applications/VMware\ Fusion.app/Contents/Library/VMware\ OVF\ Tool 
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % pwd
/Applications/VMware Fusion.app/Contents/Library/VMware OVF Tool
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ls
README.txt			open_source_licenses.txt
certs				ovftool
env				schemas
icudt44l.dat			vmware-eula.rtf
lib				vmware.eula
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptALLEulas ~/Documents/Virtual\
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptALLEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap1.vmwarevm/Mahyap1.vmx /Users/stmgroupteknoloji/Desktop/Mahyap1.ovf
Error: Unknown option: 'acceptALLEulas'
Completed with errors
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptALLEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap1.vmwarevm/Mahyap1.vmx /Users/stmgroupteknoloji/Desktop/Mahyap1.vmdk
Error: Unknown option: 'acceptALLEulas'
Completed with errors
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap1.vmwarevm/Mahyap1.vmx /Users/stmgroupteknoloji/Desktop/Mahyap1.vmdk
Opening VMX source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap1.vmwarevm/Mahyap1.vmx
Opening OVF target: /Users/stmgroupteknoloji/Desktop/Mahyap1.vmdk
Writing OVF package: /Users/stmgroupteknoloji/Desktop/Mahyap1.vmdk
Transfer Completed                    
Completed successfully
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap1.vmwarevm/Mahyap1.vmx /Users/stmgroupteknoloji/Desktop/Mahyap11.ovf
Opening VMX source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap1.vmwarevm/Mahyap1.vmx
Opening OVF target: /Users/stmgroupteknoloji/Desktop/Mahyap11.ovf
Writing OVF package: /Users/stmgroupteknoloji/Desktop/Mahyap11.ovf
Transfer Completed                    
Completed successfully
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap1.vmwarevm/Mahyap-2.vmx /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Error: Failed to open file: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap1.vmwarevm/Mahyap-2.vmx
Completed with errors
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Opening VMX source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx
Opening OVF target: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Writing OVF package: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Transfer Completed                    
Completed successfully
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % sudo
usage: sudo -h | -K | -k | -V
usage: sudo -v [-AknS] [-g group] [-h host] [-p prompt] [-u user]
usage: sudo -l [-AknS] [-g group] [-h host] [-p prompt] [-U user] [-u user] [command]
usage: sudo [-AbEHknPS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory] [-T timeout] [-u user] [VAR=value] [-i|-s] [<command>]
usage: sudo -e [-AknS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory] [-T timeout] [-u user] file ...
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % sudo su
Password:
sh-3.2# pwd
/Applications/VMware Fusion.app/Contents/Library/VMware OVF Tool
sh-3.2# ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Opening VMX source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx
Opening OVF target: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Writing OVF package: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Transfer Completed                    
Error: Output file /Users/stmgroupteknoloji/Desktop/Mahyap-2.ovf already exists. Use overwrite flag to delete it.
Completed with errors
sh-3.2# ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Opening VMX source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx
Opening OVF target: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Writing OVF package: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Transfer Completed                    
Completed successfully
sh-3.2# ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vm /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Mahyap-2.vmsd  Mahyap-2.vmx   Mahyap-2.vmxf  
sh-3.2# ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmsd /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Opening OVF source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmsd
Error:
 - Line 1: Could not parse the document: 'syntax error'.
Warning:
 - No manifest file found.
Completed with errors
sh-3.2# ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmxf /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Opening OVF source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmxf
Error:
 - Line 2: Incorrect namespace '' found.
Warning:
 - No manifest file found.
Completed with errors
sh-3.2# ls
README.txt			env				lib				ovftool				vmware-eula.rtf
certs				icudt44l.dat			open_source_licenses.txt	schemas				vmware.eula
sh-3.2# exit
exit
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Opening VMX source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx
Opening OVF target: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Writing OVF package: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Transfer Completed                    
Error: Output file /Users/stmgroupteknoloji/Desktop/Mahyap-2.ovf already exists. Use overwrite flag to delete it.
Completed with errors
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % ./ovftool --acceptAllEulas /Users/stmgroupteknoloji/Virtual\ Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Opening VMX source: /Users/stmgroupteknoloji/Virtual Machines.localized/Mahyap-2.vmwarevm/Mahyap-2.vmx
Opening OVF target: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Writing OVF package: /Users/stmgroupteknoloji/Desktop/Mahyap-2.vmdk
Transfer Completed                    
Completed successfully
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % https://github.com/openalpr/openalpr.git
zsh: no such file or directory: https://github.com/openalpr/openalpr.git
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % https://github.com/openalpr/openalpr.git
zsh: no such file or directory: https://github.com/openalpr/openalpr.git
stmgroupteknoloji@STM-MacBook-Pro VMware OVF Tool % 
