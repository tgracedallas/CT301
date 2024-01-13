# CT301

Setup Remote VSC IDE access to CSU Linux machines for CT301
& Support remote debugging

Set up and connect to the CSU VPN through Global Protect VPN. [na.cs.colostate.edu/remote-connection/vpn/](https://sna.cs.colostate.edu/remote-connection/vpn/)https://sna.cs.colostate.edu/remote-connection/vpn/

SSH to a CSU Linux machine. You can find the machines on this website. https://sna.cs.colostate.edu/remote-connection/ssh/

Set up passwordless SSH access(recommend blank passphrase). https://sna.cs.colostate.edu/remote-connection/ssh/keybased/ Verify that you can ssh to csu with simple command 'ssh your_CS_username@machine-name.cs.colostate.edu' in terminal. Then make your self a CT 301 directory. Then make yourself a directory for the specific assignment. 

<img width="762" alt="makeAssignmentDir" src="https://github.com/tgracedallas/CT301/assets/156542338/6e7690b7-b4c7-4399-a0bf-4a14aa5409a3">

Install Visual Studio Code (VSC) to your local machine. https://code.visualstudio.com/ 

Install VSC extensions: C/C++, C/C++ Themes, C/C++ Extention Pack, Remote - SSH, Remote - SSH: Editing..., Remote Explorer, CMake (by twxs), CMake Tools (all by Microsoft except for CMake)

![IMG_2987](https://github.com/tgracedallas/CT301/assets/156542338/b535ddf1-2df7-4c4d-acce-ad3b781cc1d6)
![IMG_0480](https://github.com/tgracedallas/CT301/assets/156542338/ee48c8ad-8dd2-4fb0-9c3e-097393ee967b)
![IMG_0614](https://github.com/tgracedallas/CT301/assets/156542338/3758c172-c0ac-4f96-8b64-4a06c6c07a64)

In VSC in the bottom-left corner, select icon (Open a Remote Window)<img width="1331" alt="VSC_openRemote" src="https://github.com/tgracedallas/CT301/assets/156542338/5c34636c-49fc-4941-98d7-c8c1f0f2a509">

Once the icon is selected a menu will drop down in the upper-middle of the window. Click on the connect to host option. <img width="1332" alt="VSC_connecttohost" src="https://github.com/tgracedallas/CT301/assets/156542338/7289e63f-584a-48ad-8b93-db2229958de4">

Then in the box above the menu enter your_CS_username@machine-name.cs.colostate.edu then press enter.
<img width="1330" alt="VSC_suerNameEntery" src="https://github.com/tgracedallas/CT301/assets/156542338/5a3c1a7e-0b1e-41db-a2c5-5887bd02c2cb">

Your screen should look like mine below.<img width="1333" alt="VSC_ssh_machineName" src="https://github.com/tgracedallas/CT301/assets/156542338/8f8573bb-0c3f-4502-9cf0-5e5681f8006b">

Then open your assigment directory in VSC.
<img width="1441" alt="VSC_openHW" src="https://github.com/tgracedallas/CT301/assets/156542338/ed36ae54-df34-4c79-9c99-6acb0b1c084c">


Copy your assignment files into the folder or make your own files as instructed. Make another subdirectory called .vscode. Then copy files launch.json, and tasks.json into the .vscode directory. (https://github.com/tgracedallas/CT301/blob/main/launch.json) (https://github.com/tgracedallas/CT301/blob/main/tasks.json)
<img width="1441" alt="VSC_ vscodeUpdate" src="https://github.com/tgracedallas/CT301/assets/156542338/e6116180-4eaf-4e39-bed7-893304ff753d">

Click on the extentions icon. Install CMake, CMake Tools, C/C++, C/C++ Extention Pack on your ssh machine.
<img width="1441" alt="VSC_installinSSh" src="https://github.com/tgracedallas/CT301/assets/156542338/fc7b1d8c-b934-49a5-bb73-11e392a9a3d1">

Once you have set up everything and have some code run. First select the file that has the code you want to test in it. Then the Run and Debug icon, once the debug window click on the green arrow to debug your code. <img width="1441" alt="VSC_debug" src="https://github.com/tgracedallas/CT301/assets/156542338/ecfc9d48-f714-4a16-9635-5408dc638414">













