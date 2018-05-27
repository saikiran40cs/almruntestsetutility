## Run-time error 429; ActiveX component can&#039;t create object {#run-time-error-429-activex-component-can-t-create-object}

This error may occur because the ActiveX or COM DLL being accessed is not registered on the system.

1.  Install the Microsoft .NET Framework 2.0 or greater.
2.  Reboot and delete and files in the TEMP folder on your PC. These are usually located in C:\Windows\Temp and in the %temp% environment variable.
3.  Reinstall the component package that includes the DLL being accessed. This will register the DLL.
4.  If problems continues the only reason behind the issue is there is a problem in your code. Please review your code and re-run the macros.