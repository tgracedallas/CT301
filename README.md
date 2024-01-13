# CT301

Setup Remote VSC IDE access to CSU Linux machines for CT301
& Support remote debugging

Set up and connect to the CSU VPN through Global Protect VPN. [na.cs.colostate.edu/remote-connection/vpn/](https://sna.cs.colostate.edu/remote-connection/vpn/)https://sna.cs.colostate.edu/remote-connection/vpn/

SSH to a CSU Linux machine. You can find the machines on this website. https://sna.cs.colostate.edu/remote-connection/ssh/

Set up passwordless SSH access(recommend blank passphrase). https://sna.cs.colostate.edu/remote-connection/ssh/keybased/ Verify that you can ssh to csu with simple command 'ssh your_CS_username@machine-name.cs.colostate.edu'

Install Visual Studio Code (VSC) to your local machine. https://code.visualstudio.com/ 

Install VSC extensions: Remote - SSH, Remote - SSH: Editing..., Remote Explorer, (all from Microsoft)

In VSC in the bottom-left corner, select icon (Open a Remote Window)<img width="1331" alt="VSC_openRemote" src="https://github.com/tgracedallas/CT301/assets/156542338/5c34636c-49fc-4941-98d7-c8c1f0f2a509">

Once the icon is selected a menu will drop down in the upper-middle of the window. Click on the connect to host option. <img width="1332" alt="VSC_connecttohost" src="https://github.com/tgracedallas/CT301/assets/156542338/7289e63f-584a-48ad-8b93-db2229958de4">

Then in the box above the menu enter your_CS_username@machine-name.cs.colostate.edu then press enter.
<img width="1330" alt="VSC_suerNameEntery" src="https://github.com/tgracedallas/CT301/assets/156542338/5a3c1a7e-0b1e-41db-a2c5-5887bd02c2cb">

Your screen should look like mine below.<img width="1333" alt="VSC_ssh_machineName" src="https://github.com/tgracedallas/CT301/assets/156542338/8f8573bb-0c3f-4502-9cf0-5e5681f8006b">




