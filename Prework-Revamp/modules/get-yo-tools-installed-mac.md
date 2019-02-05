# Get Your Tools Installed (Mac)

You will be installing the required tools and software for the course. There's a lot to get through, so buckle in and get ready! 

## Computer Specifications

The computer you will use in this course needs to meet the following requirements. 

* Laptop with at least 8 GB RAM and 64-bit dual processor 

  **Note:** Desktops, netbooks, thin clients, and tablets are not permitted.

* 100 GB free disk space \(300 GB preferred\)

* At least 2.0 GHz CPU

* Virtualization capable \(Check BIOS settings.\)

* USB port

* Full administrator \("root"\) privileges to operating and all software

### Additional Considerations

* If you are using a work-issued computer,  you may lack the permission to modify the system to successfully complete activities.
* Systems should have antivirus and antimalware installed. It is highly recommended that the computer be scanned for these issues and any findings remediated before attending class.
* A mouse is optional, but students may find it to be useful in completing labs efficiently.
* Students with limited free disk space may elect to purchase a external hard drive to store software and courseware. This is not a substitute for the required 100 GB of free disk space.

**Note:** If you need assistance determining these specifications, see the images below. 

### Check CPU and RAM

Click the Apple icon in the top left of your desktop screen. Select **About this Mac** from the drop-down menu. A window like the one below will pop up. Your machine's CPU and RAM will be listed here. 

![1023](assets/1023.png)



### Check Available Free Space

Click the **Storage** tab along the top of the window.

![1024](assets/1024.png)



### Check for Virtualization Capability

Launch Terminal. (On your keyboard, press **command+space**, and then type "terminal" into the Spotlight Search bar.

Type the command `sysctl -a | grep machdep.cpu.features`. The output is shown below. Look for an entry showing `VMX` \(highlighted below\).

![1025](assets/1025.png)

## Set Up Your Accounts

Let’s set up the accounts you'll be using in this course.

- LinkedIn
- GitHub
- GitLab
- Google  
- SANS
- ISACA
- ISC2
- Cisco

In addition, be sure to accept the invite for your section on Slack. You will receive the link to your class-specific channel during orientation.

### LinkedIn

1. Go to [LinkedIn](https://linkedin.com) and complete the registration process.
2. Create your profile. As recruiters often scour this site for job candidates, the minimum information on your profile should be a headshot photo, job history, education history, and relevant skills.
3. Start connecting with coworkers and friends! Build your network one connection at a time.

Looking for tips for creating an outstanding LinkedIn profile? Check out the links below.

* [22 Useful & Quick Ways You Can Improve Your LinkedIn Profile](https://www.searchenginejournal.com/improve-your-linkedin-profile/226433/)
* [How to Create an All-Star LinkedIn Profile ](http://topdogsocialmedia.com/linkedin-marketing-infographic/)

### GitHub

GitHub is a platform for coding and version control (managing frequently changing documents). Note that GitHub is optional for the class, but if you choose to create an account, you will use those same credentials for GitLab, which is required. 

Go to [GitHub](https://github.com) and complete the sign-up process.  We recommend including a headshot and contact information on your profile. 

### GitLab

GitLab is a similar platform to GitHub. We will be using Gitlab to store and retrieve course files. A separate account is not needed to access GitLab; you can you the GitHub account that was previously created. You will receive the link to your class-specific repository during orientation.

1. Go to [GitLab](https://gitlab.com/users/sign_in).

2. Click the GitHub logo (white cat on the black background\) to sign in with GitHub. You will be guided through the login process and will need to authorize the use of your GitHub credentials.

When your account is authenticated, you will see a Welcome screen. We recommend updating your profile to include a headshot and your contact information. 


### Cisco

Cisco Systems is the market leader in network equipment and network education. We will be using Cisco's program Packet Tracer, available in their learning portal NetAcad. Packet Tracer is a powerful network simulation program that allows students to experiment with networks.

As a Mac user, you will install the program on a Windows 10 virtual machine (VirtualBox), which we will walk you through below. 

1. Go to the [Packet Tracer](https://www.netacad.com/courses/packet-tracer-download/) download page.
2. Click **Enroll to download Packet Tracer**.
3. Enroll in the Introduction to Packet Tracer course by clicking **Sign up today!**
4. Complete the registration form.

**To be completed when VirtualBox is installed:**

1. Launch the Introduction to Packet Tracer course.
2. Scroll down and select the Windows installation file. 

### SANS

The SANS Institute is one of the world's leading cybersecurity training and knowledge-sharing communities. SANS stands for SysAdmin, Audit, Network, and Security. While their content is robust and heavily vetted, courses are priced at about 5,000 to 6,000 dollars for a one-week course. In this course we will use some of the members' public research and reports. 

Go to the [SANS](https://www.sans.org/account/create) sign-up page and complete the registration form.

Feel free to explore the [SANS](https://www.sans.org/) website. We suggest taking a look at their [GIAC certification pathways](https://www.giac.org/certifications/categories), [posters](https://www.sans.org/security-resources/posters/), and [reading room](https://www.sans.org/reading-room/). 

### ISACA

ISACA stands for Information Systems Audit and Control Association. ISACA's focus has traditionally been auditing, but the organization has always had a deep security side. ISACA also offers certifications, mainly in cyber leadership, risk management, and auditing. In this class we will reference material made available in the ISACA e-Library.

Go to the [Create Account](https://www.isaca.org/ecommerce/Pages/Create-Account.aspx) page on the ISACA website and complete the all four pages of the form. If you get an error message, check your email; your request may still have been processed. 

To learn more about ISACA, go [here](https://www.isaca.org/pages/default.aspx). 

### ISC2

ISC2 stands for International Information System Security Certification Consortium. This professional organization administers advanced cybersecurity certifications. You will need to create an account in order to take the certification exam as well as gain access to help documents and industry reports.

To create an account, go to the [ISC2](https://www.isc2.org/) website and click **Sign in** on the top right of the screen. Then click **Create an Account** and fill in the required information. 



## Tool and Software Installations 

Follow the instructions below to complete the installation process for all of the required tools. We will be installing the following: 

- Google Chrome
- Slack
- Terminal \(preinstalled on Mac\)
- Python (Version 3)
- VS Code
- VirtualBox
- Kali Linux
- Ubuntu Linux
- GitKraken
- Wireshark

### Google Chrome

1. If you don’t already have Chrome installed, visit the download page [here](https://www.google.com/chrome/browser/desktop/index.html).

2. Download, open, and run the installation file.

While you're at it, you should go ahead and create a Google account, iif you don't have one already, by following these steps. 

1. Go to the [sign-up page](https://accounts.google.com/SignUp?) and complete the form. 

2. Review and accept Google's Privacy Policy. 

3. Verify you are logged in by browsing to google.com and looking for a personalized icon in the top right corner, as seen in the image below:

![1034](assets/1034.png)

4. Click the grid icon to reveal the menu of Google services available to you, including Google Drive.

![1035](assets/1035.png)

### Slack

**Note:** You will receive the link to your class-specific channel during orientation.

1. Find Slack in the App Store and click **Install.**

2. To launch Slack, open the Finder window and select the Applications folder in the sidebar. Scroll until you find Slack, and double-click the Slack icon.
3. Right-click the Slack icon, click **Options**, and select **Keep in Dock**.

4. Click **Join Now**.

5. Enter your full name and optional display name, create a password, and then click **Next**.

If you already have Slack installed, you just need to add your team to the application by following these steps:

1. Click your workspace name in the top left to open the menu.

![1037](assets/1037.png)

2. Select **Sign in to another workspace**.

3. Enter your team’s Slack domain that you receive during orientation and click **Continue**.

4. Enter your email address \(the one we used to invite you\) and password to sign in.

### Terminal

* You’ll be entering your command line code through this interface. Since you’re on a Mac right now, you already have it! Just follow these steps to open the program.
  1. Press **command+space bar** to open Spotlight Search.
  2. Type **terminal** into the search and then press **Enter**.

![1038](assets/1038.png)

3. Keep this window open. 

![1039](assets/1039.png)

### Python (Version 3) 

Macs typically have Python preinstalled, but it will likely be a 2.x version. For this course, you will need version 3.x because Python 2.x has different syntax; the code written in 2.x will not run in a 3.x environment and vice versa. 

Check to see if you have Python installed by following these steps:

1. Open the terminal and enter the following command: `python3 --version`. 
   - If `Python 3.x.x` is returned, you have the correct version installed. 
   - If `Python 2.x.x` is returned, you need to install the latest version of Python.
   - If you get an error message that Python doesn't exist or something similar, you need to install the latest version of Python. 

To install Python version 3.x, follow these steps:

1. Go to the [Python](https://www.python.org/downloads/) website and download the latest version. Be sure to select the correct operating system. 
2. Follow the default installation steps. 
3. Check that you have the latest version of Python installed again by opening the terminal and entering the  `python3 --version` command. 

### VS Code

1. Go to the [VS Code](https://code.visualstudio.com/) website to download and install the latest version.

2. When the installation is complete, open VS Code and click the extensions icon in the Activity bar. 
3. In the search bar, type **Python** and download the first extension that appears.

### VirtualBox

1. Go to the [Virtual Box download page](https://www.virtualbox.org/wiki/Downloads).

![1046](assets/1046.png)

2. Select the download for OS X.
3. When the download is complete, go to your Downloads folder and click the VirtualBox file (.exe or .dmg) to initiate the installation. 
4. Follow the default installation steps. You may get a warning that you will be temporarily disconnected from the network. 
5. When the installation is complete, launch the application. If you see this screen, the installation was successful.

![1047](assets/1047.png)

As a sneak peek of what lies ahead, here is a preview of a Mac computer running an instance of Windows 7.

![1048](assets/1048.png)


### Kali Linux

For this course we will download Kali Linux VirtualBox Images, which will allow us to skip the initial installation phase. (Think of this as cloning another system that is fully set up.)  Follow these steps to complete the download process. 

1. Go to  [Kali Linux Downloads—Virtual Images](https://www.offensive-security.com/kali-linux-vmware-virtualbox-image-download/).
2. Scroll down until you see the table of download options (see the screenshot below), and click the **Kali Linux VirtualBox Images** tab. 

![1052](assets/1052.png)

3. Click **Kali Linux 64 bit Vbox** to download the file and complete the installation. 

### Ubuntu Linux

1. Go to [Download Ubuntu Desktop](https://www.ubuntu.com/download/desktop).

2. Click the **Download** button. If the download doesn't begin automatically, click **download now** on the next screen. 

   **Note:** You will be asked if you would like to donate to Ubuntu development. You can ignore this option. 

### GitKraken

1. Go to [GitKraken](https://www.gitkraken.com/).

2. Click the **Download Free Now** button. Confirm that is the correct download for your operating system; if necessary, select the correct version by clicking **See All Platforms**.

3. Locate the installation file on your computer once the download is complete. Drag the icon into your Applications folder, and then click on the icon to run the program.  

4. Log in with your GitHub credentials when prompted. You should see an interface like the one in the image below.

![1056](assets/1056.png)

### Wireshark

1. Go to the [Download Wireshark](https://www.wireshark.org/download.html) page.

2. Select **macOS** from the **Stable Release** list. 

![wireshark_mac](assets/wireshark_mac.png)

3. Open the disk image and run the enclosed installer.

![wireshark_mac_installer](assets/wireshark_mac_installer.png)

4. Click **Continue** on the Software License Agreement. 

![group-18](assets/Group-18.png)

5. Click **Agree** to continue the installation. 

![group-22](assets/Group-22.png)

6. Click **Install**, and then enter your computer password.

![group-20](assets/Group-20.png)

7. When the installation is complete, you should see the prompt below. Click **Close**.

![group-21](assets/Group-21.png)

## You're Done! 

That's all for the installations, so give yourself a pat on the back! Installations are never fun, but just like taxes, you gotta do them.

Be sure to take a break before continuing with the rest of the prework.