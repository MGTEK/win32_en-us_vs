# Offline help files for Windows Desktop App Development

Visual Studio can display online help in a webbrowser, as well as [offline help via Microsoft Help Viewer](https://docs.microsoft.com/en-us/visualstudio/help-viewer/installation).

For quite some time, the offline help files for Windows Desktop App Development are screwed up. For instance, if you enter *CreateFile* in the index, nothing (or merely related pages) will show up. If you press F1 in Visual Studio, it will usually display the online help variant.

I noticed that I had a machine with an older documentation set that was still working properly. I decided to create a help manifest that you can use to download a working version of Windows Desktop App Development. It is older documentation set from about 2018, and includes help up to Windows 10 version 1709.

## Install Windows Desktop App Development 2018

- In **Microsoft Help Viewer**, switch to the **Manage Content** tab and uninstall broken books, such as **Windows Desktop App Development** and **Programming reference for Windows API**.
- Click the **Update** button to remove the broken books.
- Select the Installation source **Disk** and enter the following URL: https://raw.githubusercontent.com/mgtek/win32_en-us_vs/master/helpcontentsetup.msha
- Select **Windows Desktop App Development (2018)** and click **Add** and then **Update** to install the book.
