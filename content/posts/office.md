---
title: "Office"
date: 2022-06-05T15:45:39+09:30
draft: false
categories: ["office"]
---

Download all Office 365 Microsoft apps for free!

# ⊞ Windows
## Preparation
- You will need [7zip](https://7-zip.org) or a similar file manager.

## Office Deployment Tool
1. Download the [Office Deployment Tool](https://www.microsoft.com/en-us/download/details.aspx?id=49117).

2. Double click to run the downloaded .exe

3. Create a folder to save the contents to. Make sure you know where you save the files.

4. Go to the files in the folder and delete all except for ```setup``` and ```configuration-Office2021Enterprise```.

5. Right click on the ```configuration-Office2021Enterprise``` file and open it with notepad or any text editor.

6. Delete these lines:
```
<Product ID="VisioPro2021Volume">
<Language ID="en-us"/>
</Product>
<Product ID="ProjectPro2021Volume">
<Language ID="en-us"/>
</Product>
```
7. Save the file and close it.

8. Right click inside the folder (with the ```setup``` and ```configuration-Office2021Enterprise```) and click "open a powershell window here. (In Windows 11 you may need to go to "more options" first.)

9. In the powershell window paste this command in by right clicking:
``` .\setup.exe /configure .\configuration-Office2021Enterprise.xml ```

10. Click enter.

11. The installer should open and the Office apps will be installing. 

12. Upon completion, all the apps will be installed. To activate the apps proceed below.

## Activate The Office Apps
1. Download [MAS](https://github.com/massgravel/Microsoft-Activation-Scripts/releases/tag/1.5).
2. Extract the folder with [7zip](https://7-zip.org), the password is ```1234```.
3. Open the folder ```All-In-One-Version``` and run the .cmd file
4. Enter ```3``` for Office activation
5. On the next page enter ```2``` for Office activation
6. Done! All Office apps are now activated!

# Comments
Let me know what you think below!
{{< chat office >}}
