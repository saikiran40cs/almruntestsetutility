# HP ALM Client Registration {#hp-alm-client-registration}

HP ALM Client Registration enables you to deploy and register the following ALM components on a client machine:

*   HP ALM Client components
*   HP ALM Site Administration Client components

For a list of the tools for which you must register ALM on a client machine, refer to the _HP Application Lifecycle Management Installation Guide_.

**Installation Instructions:**

1.  Log on to the machine as a local user or a domain user with administrator privileges. Ensure that you have the file system and registry permissions listed below.
2.  Register and deploy components on your client machine:
    1.  Click **Register HP ALM** below for ALM Client components.
    2.  Click **Register HP ALM Site Administration** below for ALM Site Administration Client components.

**Note:**

*   After components are registered on the client machine by a user with administrator privileges, users without administrator privileges can start ALM client components. 

**Required Permissions:**

You must have the following file system permissions:

*   Full read and write permissions on the **HP\ALM-Client** deployment folder. This is located at:
    1.  **Windows 7, 2008, 2008R2:** %ALLUSERSPROFILE%
    2.  **Windows XP:** %ALLUSERSPROFILE%\Application Data
*   Full read and write permissions to the **Temp** (**%TEMP%** or **%TMP%**) directory. The installer program writes installation and log files to this directory. This is generally located at:
    1.  **Windows 7, 2008, 2008R2:** C:\Users\&lt;username&gt;\AppData\Local\Temp
    2.  **Windows XP:** C:\Documents and Settings\&lt;username&gt;\Local Settings\Temp

You must have full read and write permissions on the following registry keys:

*   **HKEY_CLASSES_ROOT**
*   **HKEY_CURRENT_USER\Software**
*   **HKEY_LOCAL_MACHINE\SOFTWARE**

**Versions supported:** HP Application Lifecycle Management 11.52.