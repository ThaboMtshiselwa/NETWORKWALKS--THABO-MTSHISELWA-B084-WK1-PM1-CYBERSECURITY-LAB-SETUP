# cybersecurity-lab-setup-ip-address-internet-configuration-networkwalks-w1
Cybersecurity Lab Setup, IP Address Configuration and Internet Testing
# To set up your lab you will need the following applications for your Cybersecurity Virtual Machine
N.B Ensure you have a application like winzip or 7zip. I have winzip which is fine to extract the files downloaded in zip file.
1. Download and Install the lastest version of VirtualBox 7.2.22 platform packages (download the extension file compatible with your operating system)
   https://virtualbox.org/wiki/Downloads
   <img width="940" height="474" alt="image" src="https://github.com/user-attachments/assets/84cc8682-cce2-4ee3-a463-f3703a458be5" />
   Should you encounter issues or an error stating download microsoft visual C++ 2019/restart your machine and install again, install the latest version of Microsoft Visual C++ Latest supported v14 (for Visual Studio 2017–2026) Redistributable compatible with your device. Visit https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170 for extension file. Once complete set up network settings.
   
   Configure the network settings on your Virtualbox (create NATNetwork in 10.0.0.0/24)
   > Select File, Tools, Network then NATNetwork and use the below prompts.
   > Use IPv4 10.0.0.0/24
   > Ensure Enable DHCP is selected, then click apply
   > <img width="940" height="499" alt="image" src="https://github.com/user-attachments/assets/85bc3a30-69ca-4f2f-b59a-8c66fe371928" />
2. Download & import Kali Linux Virtual Machine in your Virtualbox. Setup the IP configuration of Kali Linux https://kali.org/get-kali
   <img width="940" height="476" alt="image" src="https://github.com/user-attachments/assets/e2c64587-0b41-4d91-9f44-efb6b91f5fb2" />
   Navigate to Prebuilt Vitual Machines
   Kali Linux VMware & VirtualBox images are available for users who prefer, or whose specific needs require a virtual machine installation.
   In my case I downloaded the VituaL Machine which is about 3.6GB. Once done download extract the zip file.
   The default credentials "Username: kali and Password: kali". This you will use when logging into your virtual server.

   On your installed Virtualbox navigate to:
   > Select Machine under Tool (other versions will have then defaulted in your navigation bar)
   > Click on open, then select the file extracted from your Kali Linux folder "kali-linux-2026.2-virtualbox-amd64-1.16"
   > Once selected and loaded to VirtualBox, click start
   <img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/e3c616b3-2309-4e5a-855e-d0966cec53b8" />
   Give it a few seconds and your Kali Linux will open and request for Login information which I disclosed above.
   <img width="1915" height="1017" alt="image" src="https://github.com/user-attachments/assets/7b40c30f-d7f8-4824-9653-93f128966ceb" />

   Configure Network Settings
   > From here we configure our network settings and testing our internet access through web browser. If you have access then your network settings are correct.
   > If experiencing issues, normally on the newer versions of Kali Linux. You will run the below Commands.
   Navigate to Network

