# MMFml
Utilizing MMF as a execution space for shell code

MMFml is a POC framework that sets up a space with the system memory map for code execution. 
The initial POC is written C#.NET and is oh-so-alpha, the shellcode within the .cs file is /x64 cmd.exe -c calc.exe but we expect you will strip the code.
We've also converted the POC to PowerShell.
