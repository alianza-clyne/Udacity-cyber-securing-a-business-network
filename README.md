# Udacity Cybersecurity Course #1 Project - Securing a business network for Joe's Auto

Learning​ ​Objectives:
● Explain security fundamentals including core security principles, critical security controls, and cybersecurity best practices.
● Evaluate specific security techniques used to administer a system that meets industry standards and core controls
● Assess high-level risks, vulnerabilities and attack vectors of a sample system
● Explain methods for establishing and maintaining the security of a network, computing
environment, and application.
Cybersecurity ND #1 Project Template Page | 1
 Student Information
Student Name: Alianza Clyne-Roberts Date of completion: January 21, 2021
Cybersecurity ND #1 Project Template Page | 2

 Scenario
Congratulations!
You have been hired to secure the PC used at your friend’s business: Joe's Auto Body. Joe provides car repair services throughout the tri-state area. He's had previous employees use it for activities un-related to work (e.g., web browsing, personal email, social media, games, etc.) and he now uses it to store his critical business information. He suspects that others may have broken into it and may be using it to transfer files across the internet. He has asked that you secure it for him according to industry best practices, so it can be once again used as a standard PC.
You will be given access to a virtual image of Joe’s Auto Body’s PC. It’s a copy of the actual computer operating system in use that will be transferred to Joe’s computer once you are done.
This template provides you with the high-level steps you’ll need to take as part of securing a typical computer system. For each step, use the virtual Windows 10 PC to answer the questions and challenges listed in this project. You’ll also need to explain how you got the answers and provide screenshots showing your work.
It’s important that you read through the entire document before securing the system and completing this report.
To start, you need to login to the virtual PC. You can use Joe’s account using the user-id and password below. You may also use any other account on the PC.
Account Name: JoesAuto Password: @UdacityLearning#1
Cybersecurity ND #1 Project Template Page | 3

 1. Reconnaissance
The first step in securing any system is to know what it is, what’s on it, what it’s used for and who uses it. That’s the concept of systems reconnaissance and asset inventory. In this step, you’ll document the hardware, software, user access, system and security services on the PC.
Complete each section below.
Hardware
1. Fill in the following table with system information for Joe’s PC.
  Device Name Processor
Install RAM System Type Windows Edition Version
Installed on OS build
JOESGARAGEPC
Intel(R) Xeon(R) Platinum 8171M CPU @ 2.60GHz, 2095 Mhz, 1 Core(s), 1 Logical Processor(s)
1.00 GB
x64-based PC
Microsoft Windows 10 Pro
Version 10.0.17763 Build 17763
Virtual Machine
17763.1158
                              2. Explain how you found this information:
I retrieved the Device Name, Processor, Install RAM, System Type, Windows Edition, Version, Installed On information by taking the following steps:
Go to the Windows Search Bar > Type “System Information” > Click open > Click System Summary > This will show the system information.
I retrieved the OS build by taking the following steps:
Go to the Windows Search Bar > Type “Settings” > Click open > Click System > Scroll down and click About > This will show some of the system information such as the OS build.
3. Provide a screenshot showing this information about Joe’s PC:
Cybersecurity ND #1 Project Template Page | 4

   Software
Another common early step in securing is taking an inventory of software or applications installed on a computer system. These are programs outside of the standard operating system.
Cybersecurity ND #1 Project Template Page | 5

 1.
● ● ● ● ● ●
● ● 2.
List at least 5 installed applications on Joe’s computer:
7-Zip
Google Chrome
MusicBee
Npcap
Streaming Audio Recorder Plus VLC Media Player
VNC Server
VNC Viewer
Explain how you found this information. Provide screenshots showing this information.
Go to
and Features > This will show a list of the installed applications.
the Windows Search Bar > Type “Control Panel” > Click open > Click Programs > Click Programs
Cybersecurity ND #1 Project Template Page | 6

   Cybersecurity ND #1 Project Template Page | 7

  An alternative way is to go to the Windows Search Bar > Type “Settings” > Click open > Click Apps > This will show a list of the applications and features.
 Cybersecurity ND #1 Project Template Page | 8

 3. The Center for Internet Security Controls lists this as one of their steps for security. Which step does this fulfill?
This fulfills step 2 - Inventory and Control of Software Assets. This step involves actively managing and monitoring all software that is on the network. This reduces or eliminates the risk of unauthorized software being installed or executed.
Accounts
As part of your security assessment, you should know the user accounts that may access the PC.
1. List the names of the accounts found on Joe’s PC and their access level.
   Account Name
AUser DefaultAccount
Guest
JoesAuto Notadmin
WDAGUtilityAccount
Full Name
A User N/A
N/A
Joes Account Do Not Use
N/A
Access Level
Users / Standard user System managed accounts group
Guests
Administrators Remote desktop users Users
N/A
             Frank
   Frank
    Remote desktop users Users
Standard user
 Hacker
   A Hacker
    Administrators Remote desktop users Users
 JaneS
 Jane Smith
  Administrators Remote desktop users Users
               2. Provide a screenshot of the Local Users.
Cybersecurity ND #1 Project Template Page | 9

   Cybersecurity ND #1 Project Template Page | 10

 Services
Services are applications often running in the background. Most of them provide needed functionality for the PC. Some may also be used to violate security policies.
1. Provide a screenshot of the services running on this PC.
  Cybersecurity ND #1 Project Template Page | 11

 Security Services
Joe wants to ensure that standard security services are running on his PC. He’s content with using default Windows security settings and applications except for the rules outlined later. ​Reminder that at this point you are just reporting what you observe. Do not make any changes to security settings yet.
1. To view a summary of security on Windows 10, start from the ​Control Panel​. Use the “Find a setting” bar and search on Windows Defender. You can also search for Windows Defender using the Windows Run bar. Take a screenshot of what you see on the Windows Security screen and include it here:
Cybersecurity ND #1 Project Template Page | 12

   Cybersecurity ND #1 Project Template Page | 13

 2. The Windows 10 Security settings are also found from the​ Control Panel > System and Security > Security and Maintenance.​ Start by viewing ​“Review your computer’s status and resolve issues.”​ Provide a screenshot of this below:
  Cybersecurity ND #1 Project Template Page | 14

 3. Click on View in Windows Security to see the status there. Provide a screenshot of the ​Firewall settings.
 4. From the C​ ontrol Panel,​ go to ​System and Security​. In that window, select ​Windows Defender Firewall.​ Provide a screenshot of it here:
 Cybersecurity ND #1 Project Template Page | 15

 5. PC users should be notified whenever there is a security or maintenance message. In the Security & Maintenance window, click on Change Security and Maintenance settings and take a screenshot. Paste it here:
 6. Document the status of the PC’s security settings listed below. Include the process you used to determine this information along with any screenshots. At this point, you are only documenting what you find. Do not make changes (yet).
Security Feature Status
   Firewall product and status – Private network
   Status​: Firewall is off.
Process to determine this:
Go to the Windows Search Bar > Type “Firewall & network protection” > Click Open > Scroll down to Private Network
Screenshot:
 Cybersecurity ND #1 Project Template Page | 16

               Firewall product and status – Public network
 Status​: Firewall is on.
Process to determine this:
Go to the Windows Search Bar > Type “Firewall & network protection” > Click Open > Scroll down to Public Network
Screenshot:
  Virus protection product and status
   Status​:
Antivirus - Windows Defender Antivirus is turned on.
Firewall - Windows Firewall is off and your device may be unprotected.
Web protection - There is no web protection software listed.
Process to determine this:
 Cybersecurity ND #1 Project Template Page | 17

         Go to the Windows Search Bar > Type “Virus & threat protection” > Click Open > Click Manage Providers on the right side > This shows the security providers
Screenshot:
      Internet Security messages
 Status​:
Internet security settings - Currently not monitored
Process to determine this:
Go to the Windows Search Bar > Type “Security and maintenance” > Click Open > Click on the arrow next to the Security section > This shows the monitoring status
Screenshot:
  Network firewall messages
   Status​:
Network firewall - Currently not monitored
Process to determine this:
 Cybersecurity ND #1 Project Template Page | 18

         Go to the Windows Search Bar > Type “Security and maintenance” > Click Open > Click on the arrow next to the Security section > This shows the monitoring status
Screenshot:
      Virus protection messages
 Status​:
Virus protection - Currently not monitored
Process to determine this:
Go to the Windows Search Bar > Type “Security and maintenance” > Click Open > Click on the arrow next to the Security section > This shows the monitoring status
Screenshot:
  User Account Control Setting
   Status​:
User Account Control - Currently not monitored
Process to determine this:
 Cybersecurity ND #1 Project Template Page | 19

        Go to the Windows Search Bar > Type “Security and maintenance” > Click Open > Click on the arrow next to the Security section > This shows the monitoring status
Screenshot:
  7. Now that you are familiar with the security settings on Joe’s PC, explain at least three vulnerabilities and risks with these settings. In other words, what can happen to Joe’s PC if these are not changed?
[Hint: Refer to the CIS Controls document for ideas.]
● The network firewall is currently not being monitored. As such, any threats may go undetected. It is critical to turn the firewall on.
● The internet security settings are currently not being monitored. As such, any threats may go undetected. It is critical to turn this feature on.
● The user account control settings are currently not being monitored. As such, any changes to software may go undetected. It is critical to turn this feature on.
● The firewall is off for private networks. As such, any threats may go undetected. It is critical to turn the firewall on.
2. Securing the PC
Baselines
Joe has asked that you follow industry standards and baselines for security settings on this system.
1. What industry standard should Joe use for setting security policies at his organization and justify your choice?
Joe should utilize the ISO 27000 Series to set security policies at his organization. The ISO 27000 Series is a wide-ranging information security framework that Joe can use to audit his technological systems and create an effective information security program.
Cybersecurity ND #1 Project Template Page | 20

 2. What industry baseline do you recommend to Joe? [Hint: Look in the documents folder]
I recommend Joe should use the 20 Center for Internet Security (CIS) Controls. The CIS Controls will guide Joe in performing an inventory and control of his hardware and software assets; continuous vulnerability management; analyzing and modifying administrative privileges; and several other important steps for securing his auto shop’s systems.
The System and Security functions in the Windows Control Panel are where you can establish the security settings for the PC. This is found from the Control Panel > System and Security > Security and Maintenance. On the Security and Maintenance window, you see a synopsis of the Windows 10 security settings.
3. Assume Joe uses the CIS as his baseline, what controls or steps does this meet? This step meets the following controls and steps:
Basic CIS Controls
1. Inventory and Control of Hardware Assets
2. Inventory and Control of Software Assets
3. Continuous Vulnerability Management
4. Controlled Use of Administrative Privileges
5. Secure Configuration for Hardware and Software on Mobile Devices, Laptops, Workstations and Servers
Foundational CIS Controls
7. Email and Web Browser Protections
8. Malware Defenses
9. Limitation and Control of Network Ports, Protocols and Services
11. Secure Configuration for Network Devices, such as Firewalls, Routers and Switches 12. Boundary Defense
13. Data Protection
System and Security
At this point, you need to enable security services for this PC. Pick ​at least 3​ of the following 5 areas to secure in order to satisfactorily meeting the project requirements:
            Cybersecurity ND #1 Project Template Page | 21

 ● Firewall
● Virus & Threat Protection
● App & Browser Control
● User Account Control settings ● Securing Removable Media
Firewall
You need to ensure the Windows Firewall is enabled for all network access.
1. Explain the process you take to do this.
Go to the Windows Search Bar > Type “Firewall & network connection” > Click Open > Click Turn On under Domain Network > Click Turn On under Private Network
2. Include screenshots showing the firewall is turned on.
Firewall off:
  Cybersecurity ND #1 Project Template Page | 22

 Firewall turned on:
 3. What protection does this provide?
Using a firewall will ensure that all incoming and outgoing network traffic is monitored and controlled. This can serve as an additional form of protection for Joe’s IT systems.
Virus & Threat Protection
You need to ensure the Windows Defender anti-virus is enabled to always protect against current threats. It should be set to automatically update and continually scan the PC for malicious software. Note: Ignore any alerts about setting up OneDrive.
1. Explain the process you take to do this.
2. Include screenshots to confirm that anti-virus is enabled.
Cybersecurity ND #1 Project Template Page | 23

 Once you determine that virus & threat protection is on and updated, you need to turn on messages about the Network firewall and Virus protection. Refer to the instructions above for viewing the settings within Security and Maintenance, Review recent messages and resolve problems.
1. Turn on the Network firewall and Virus protection messages using Change Security and Maintenance Settings.
2. Show a screenshot here of them enabled.
3. Provide at least two risks mitigated by enabling these security settings:
● ●
4. From the CIS baseline controls, provide the controls satisfied by completing this.
App & Browser Control
The App protection within Windows Defender helps to protect your device by checking for unrecognized apps and files and from malicious sites and downloads. Review the settings found within the ​Account protection window, and App​ ​&​ ​browser control windows​ found on the Windows Defender Security page​.
Advanced students: You should also review the settings on the Exploit protection page.
1. Change the settings to provide m​ aximum​ protection for Joe’s PC and provide a screenshot of your results.
 Cybersecurity ND #1 Project Template Page | 24

 Account protection screen:
 App & browser control screen:
Cybersecurity ND #1 Project Template Page | 25

  Cybersecurity ND #1 Project Template Page | 26

  User Account Control Settings
Joe wants to prevent potentially harmful programs from making changes and wants to be notified whenever apps try to make changes to his computer. This is done through the User Account Control Setting.
1. What is the current UAC setting on Joe’s computer?
This is available from the above security settings.
2. What should it be set to? Include a screenshot of the new setting.
Securing Removable Media
A security best practice is to not allow the use of removable hard drives (USB sticks, Memory Cards, and DVDs). They are needed as part of Joe’s backup policy. The next best thing is to make sure that any applications don’t automatically start when the media is inserted and the user is
 Cybersecurity ND #1 Project Template Page | 27

 asked what should happen. This is set from the Control Panel > Hardware and Sound > Autoplay menu.
1. On Joe’s computer, go to that function and deselect “Use AutoPlay for all media and devices.”
 2. For the Removable Drive, make the default, “Ask me every time.” Include a screenshot of your results.
Cybersecurity ND #1 Project Template Page | 28

  3. Securing Access
Ensuring only specific people have access on a computer system is a common step in information security. It starts by understanding who should have access and the rules or policies that need to be followed.
On Joe’s computer, only the following accounts should be in use:
● JoesAuto
● Jane Smith (Joe’s assistant)
● A User - Used for exercises (Not used in this project)
● Notadmin - Built-in administrator account (Not used for this project)
● Windows built-in accounts: Guest, DefaultAccount, and WDAGUtility (Not used for this project)
Joe’s Auto Access Rules:
● Only JoesAuto and A User should have administrative privileges on this PC. X
● Joe wants to prevent potentially harmful programs from making changes and wants to be
notified whenever apps try to make changes to his computer. X
● All valid users should have a password following Joe’s password policy below X
Cybersecurity ND #1 Project Template Page | 29

 o At least 8 characters
o Complexity enabled
o Changed every 120 days
o Cannot be the same as the previous 5 passwords
● Account should be automatically disabled after 5 unsuccessful login attempts. The account should be locked for 15 minutes and then should automatically unlock. X
● Upon first logging into the PC, Joe wants a warning banner letting anyone using to know that this is to only be used for work at Joe’s Auto Body shop by authorized people.
● There is to be no remote access to this computer. User Accounts
1. What user accounts should not be there?
The following user accounts should be be on the computer: Frank and Hacker
2. Bonus questions: What is Hacker’s password?
I can reset Hacker’s password and create a new password.
3. Explain the steps you take to disable or remove unwanted accounts.
Search for Computer Management > Click Open > System tools > Local users and groups > Users > Disable account steps: Double click user (Frank or Hacker) > Check Account is disabled button Delete account steps: Right click user (Frank or Hacker) > Right click user > Click Delete > Click Yes
4. Why is it important to disable or remove unneeded accounts from a PC or application? Include potential vulnerabilities and risks.
It is critical to remove unneeded accounts to reduce the likelihood of an insider or outsider threat using the accounts to steal data, delete data, or commit cyber attacks against Joe’s Auto.
If this account is not actively being monitored, Joe will likely not discover that the accounts are being used to attack his computer for an extended period of time.
Only specific accounts should have administrator privileges. This reduces the ability for unwanted applications to be installed including malware.
5. Which account(s) have administrator rights that shouldn’t?
The following accounts should not have administrator rights: Hacker and JaneS
6. Explain how you determined this. Provide screenshots as needed.
Cybersecurity ND #1 Project Template Page | 30

 Search for Computer Management > Click Open > System tools > Local users and groups > Users > Double click user (J​ aneS​ or Hacker) > Click on the Member Of tab > This will confirm if the user is an administrator
 Administrator privileges for too many users are another security challenge.
7. Provide at least three risks associated with users having administrator rights on a PC.
● An administrative account will allow unauthorized users to remove authorized users. This can prevent authorized users from being able to access the PC.
● An administrative account will allow unauthorized users to download applications, malware, adware, spyware, or ransomware to the PC. This can compromise the confidentiality, integrity, and availability of the data on the PC.
● An administrative account will allow unauthorized users to open unsafe ports or enable remote connections. This can be used by threat actors to remotely access confidential information on the PC.
Now you need to remove administrator privileges for any user(s) that should have it.
Cybersecurity ND #1 Project Template Page | 31

 8. Explain the process for doing this. Include screenshots to show your work.
Search for Computer Management > Click Open > System tools > Local users and groups > Users > Double click user (J​ aneS​ or Hacker) > Click on the Member Of tab > Select Administrators > Click the Remove button > Click Ok button
Before removal:
 After removal:
Cybersecurity ND #1 Project Template Page | 32

  9. What is the security principle behind this?
This is the principle of least privilege. This principle requires that users receive the least amount of access or permissions needed to perform their job functions.
10. The Center for Internet Security Controls lists this as one of their steps for security. Which step does this fulfill?
This step fulfills the following control: Basic CIS Controls - ​4. Controlled Use of Administrative Privileges
Setting Access and Authentication Policies
After you talked with Joe about security, he has asked that the access rules outlined above be in place on his PC. These are set using the Local Security Policy function in Windows 10. On the Windows search bar, type “​Local Security Policy”​ to access it. Click the > arrow next to both “​Account Policies”​ and “​Local Policies”​ and review their contents.
 Cybersecurity ND #1 Project Template Page | 33

 1. Provide a screenshot of the Local Security Policy window here.
[Note: Local Security Policy is not available on Windows 10 Home edition.]
 2. Explain the process for setting the password and access control policies locally on a Windows 10 PC. Provide screenshots showing how you set the rules on the PC.
● Setting the Password Policy:
On the Windows search bar, type “​Local Security Policy​” to access it. Click the > arrow next to “​Account Policies”​ > Password Policy >
At least 8 characters - Double click Minimum password length > Type 8 > Click Ok
Complexity enabled - Double click Password must meet complexity requirements - Click Enable > Click Ok
Changed every 120 days - Double click Maximum password age > Type 120 > Click Ok
Cannot be the same as the previous 5 passwords - Double click Enforce password history > Type 5 > Click Ok
Cybersecurity ND #1 Project Template Page | 34

 Before change:
 After change:
Cybersecurity ND #1 Project Template Page | 35

  ● Setting the Account Lockout Policy:
On the Windows search bar, type “​Local Security Policy​” to access it. Click the > arrow next to “​Account
Policies”​ > Account Lockout Policy >
Account should be automatically disabled after 5 unsuccessful login attempts - Double click Account
lockout threshold > Type 5 > Click Ok
The account should be locked for 15 minutes and then should automatically unlock - Double click Account lockout duration > Type 15 > Click Ok > This will also update ‘Reset account lockout after’ to 15 minutes
Before change:
Cybersecurity ND #1 Project Template Page | 36

  After change:
Cybersecurity ND #1 Project Template Page | 37

  Auditing and Logging
Security best practices like those found in the CIS Controls or NIST Cybersecurity Framework require systems to log events. You need to enable the Audit Policy for Joe’s PC to meet these standards.
1. From the Local Security Policy window, select Audit Policy and make applicable changes to Joe’s PC to enable minimal logging of logon, account, privilege use and policy changes.
On the Windows search bar, type “​Local Security Policy​” to access it. Click the > arrow next to “​Local Policies”​ > Audit Policy > Double click each policy > Select Success and Failure
2. Provide a screenshot of your changes here.
Cybersecurity ND #1 Project Template Page | 38

 Before change:
 After change:
Cybersecurity ND #1 Project Template Page | 39

  4. Securing Applications
As part of the inventory process, you determined computer programs or applications on the PC. The next step is to decide which ones are needed for business and which ones should be removed. Unneeded programs could be vulnerable to attacks and allow unauthorized access into the computer. They also consume system resources and could also violate licensing agreements.
Joe has established the following rules regarding PC applications:
● Joe wants everyone to use the latest version of the Chrome browser by default.
● There should be no games or non-work-related applications installed or downloaded.
● Joe is also concerned that there are “hacking” programs downloaded or installed on the PC that
should be removed.
● This PC is used for standard office functions. The auto-body has a separate service they use for
their website and to transfer files from their suppliers.
Remove unneeded or unwanted applications
1. List at least three application(s) that violate this policy.
● Spotify
● Candy Crush Friends
● Farm Heroes Saga
Cybersecurity ND #1 Project Template Page | 40

 2.
● ● ●
●
3.
Name at least three vulnerabilities, threats or risks with having unnecessary applications:
Unneeded programs could be vulnerable to attacks especially if they are not updated.
Unneeded programs could allow unauthorized access into the computer.
Unneeded programs will consume system resources. This can lead to Joe needing to spend additional money for computer storage.
Unneeded programs could violate licensing agreements.
Joe wants you to make sure unneeded applications or programs are no longer on the PC. Explain the steps you take to disable or remove them. Include screenshots to show your work.
Go to Control Panel > Uninstall a Program > Right click and uninstall Alternatively, go to Settings > Apps > Click on application > Click Uninstall
Before uninstall:
 After uninstall:
Cybersecurity ND #1 Project Template Page | 41

  Default Browser
As mentioned in the policy, Joe wants all users to use Chrome as their browser by default.
1. Explain how you set default applications within the Windows 10 operating system. Include screenshots as necessary.
Search for Default Apps > Click Choose a Default to set a default application > Alternatively, you can scroll down to the bottom and choose default apps by file type, protocol, or app.
Cybersecurity ND #1 Project Template Page | 42

  Cybersecurity ND #1 Project Template Page | 43

  2. Why should Internet Explorer be disabled from Windows PCs? Provide at least two risks or vulnerabilities associated with it.
● Over the years, Internet Explorer has had several vulnerabilities. For example, Internet Explorer has a bug that can be exploited by hackers to execute remote code on a target device and seize administrative privileges. This can pose a risk to Joe’s PC.
● Microsoft plans to end support for Internet Explorer 11 on August 17th, 2021. Without support, Internet Explorer’s vulnerability to attacks will increase. This can harm Joe’s PC and network.
Because of the reasons you give above, Internet Explorer should be removed. To do that, go to the Control Panel​, select ​Programs​. On the ​Programs and Features​ window, select “​Turn Windows features on or off​.”
3. Provide a screenshot showing Internet Explorer 11 is off.
Cybersecurity ND #1 Project Template Page | 44

  Windows Services
There are Windows features running on Joe’s computer that could allow unwanted activity or files. He suspects that someone may have used the PC as a web server in the past. Joe wants you to confirm if web services are turned on, stop it if it is and make sure it is not running whenever the computer restarts.
1. How did you determine these services were running? Include screenshots to show how you found them.
Search for Services > Click open > Scroll down to find unneeded services
Cybersecurity ND #1 Project Template Page | 45

   Cybersecurity ND #1 Project Template Page | 46

  2. Advanced users should provide at least two methods for determining a web server is running on a host - Optional
3. How do you disable them and make sure they are not restarted?
Search for Services > Click open > search for unneeded services > double click > Click Stop if service is running > Under StartUp Type, select the ‘Disabled’ in the drop down list
4. Advanced Users: The File Transfer Protocol FTP service is also running on this PC and shouldn’t. Explain the process for disabling it and ensuring it is not automatically restarted.
Search for Services > Click open > Microsoft FTP service > double click > Click Stop > Under StartUp Type, select the ‘Disabled’ in the drop down list
Patching and Updates
Keeping the operating system current on patches and fixes is a critical part of security. Joe wants his PC to be on the latest version of Windows 10. He also wants you to set it up for automated updates.
1. Explain the process for doing this. Include screenshots as needed.
Check for updates: Search for ‘Check for updates’ in the Windows bar > Click Download
Set up automated updates: Search for ‘Check for updates’ in the Windows bar > Click Advanced options at the bottom > Click the ‘On’ toggle under ‘Automatically download updates'
Cybersecurity ND #1 Project Template Page | 47

   Cybersecurity ND #1 Project Template Page | 48

  2. Go ahead and update this PC to the latest version. Warning this may take a while and require numerous restarts. When it is complete, provide a screenshot showing the PC is on the latest version.
 All applications should also be up to date on patches or fixes provided by the manufacturer. Any old versions of software should be uninstalled.
3. List at least two applications on Joe’s PC that are out of date. List them below:
● Adobe Reader
● Google Chrome
4. Explain the steps you took to determine this information.
I manually checked applications for updates.
Open Adobe Reader > Click ‘Help’ > Check for updates Open Google Chrome > Click ‘Settings’ > Check for updates
Cybersecurity ND #1 Project Template Page | 49

 5. Explain the steps for updating each of these applications. Include screenshots as needed.
I manually checked applications for updates.
Adobe Reader Update:
Open Adobe Reader > Click ‘Help’ > Check for updates > Download
 Cybersecurity ND #1 Project Template Page | 50

  Google Chrome Update:
Open Google Chrome > Click Help > Click About Google Chrome > Check for updates > Update
Cybersecurity ND #1 Project Template Page | 51

  Cybersecurity ND #1 Project Template Page | 52

  5. Securing Files and Folders
Joe has some work files in his Business folder that he wants to secure since they contain his customer information. They are labeled “JoesWork.”
Joe suspects that other users on this computer beside him and Jane can see and change his business files. He wants you to check to make sure that only those two users have privileges to view or change the files.
Encrypting files and folders
1. Explain the process for checking this and changing any necessary settings on the file. Include screenshots showing that ONLY Joe and Jane have permissions to change Joes work files. [Hint: Right-click the folder and select Properties.]
View or change
1st Step:​ Go to File Explorer > Documents > Right click on the Business Files folder > Click Properties > Clicking Sharing > Click Share > Remove ‘A Hacker’ > Add ‘Jane’ and provide Read/Write permissions > Click Share
2nd Step: ​Go to File Explorer > Documents > Right click on the Business Files folder > Click Properties > Click Security > Click Edit > Remove ‘Administrators’ and ‘Systems’ > Click Ok
Before change:
Cybersecurity ND #1 Project Template Page | 53

   Cybersecurity ND #1 Project Template Page | 54

 After change:
 Cybersecurity ND #1 Project Template Page | 55

  2. Joe wants his work files encrypted with the password, “​SU37*$xv3p1​” Explain how you would do this. What encryption method do you recommend? You may use the pre-installed program 7-Zip for this.
Search for 7-Zip File Manager in Windows search bar > Click Open > Click business files > Click Add > Enter SU37*$xv3p1 as the password > Use AES-256 > Check ‘Encrypt File Names’ > Click
Encrypting a file name in addition to its contents can help to ensure that no one can infer the contents of a file based on its name.
Cybersecurity ND #1 Project Template Page | 56

  3. What security fundamental does this provide?
Encryption protects the confidentiality and integrity of Joe’s sensitive information.
4. The Center for Internet Security Controls lists this as one of their steps for security. Which step does this fulfill?
Foundational CIS Controls - ​13. Data Protection Shared Folders
Shared folders are a common way to make files available to multiple users. There’s a folder under Joe’s documents called “Business Files” that Joe wants shared with his administrator Jane.
1. Explain how you would do that and provide a screenshot showing how you can do it. Make sure it’s only shared between Joe and Jane.
Go to File Explorer > Documents > Right click on the Business Files folder > Click Properties > Clicking Sharing > Click Share > Add ‘Jane’ and provide Read/Write permissions > Click Share
 Cybersecurity ND #1 Project Template Page | 57

  2. For advanced students: Joe wants to make sure there are no other folders shared on the PC. Explain how you view all shared files and folders on a Windows 10 PC. Include a screenshot as proof.
6. Basic Computer Forensics (Optional)
Joe has asked that you investigate his PC to see if there are any other files left behind by previous unwanted users that may show they wanted to harm Joe’s business. Look through the unwanted users’ folders and list suspicious files. General students should document three issues and advanced students at least five issues. Include a brief explanation of their contents and their risks. [Hint: there is a “Hacker” in the PC]
● Users > Hacker > Desktop > JaneSmith > Text file says Jane Smith’s password is her birthday > This can allow the hacker and other unauthorized users to access Jane’s accounts and commit cyber attacks against Joe’s Auto.
● Users > Hacker > Documents > Bank files > Pete letter > The hacker wrote a letter to Pete advising him that they stole Joe’s customers’ bank account information. There is another
Cybersecurity ND #1 Project Template Page | 58

document that contains their account information. This information can be used by the hacker
and Pete to steal money from the customers’ bank accounts.
● Users > Hacker > Documents > Joe’s invoice note > Pete asked the hacker to send an invoice to
Joe. He noted that Joe does not pay attention to who he is paying and that the invoice should be sent when Jane is out-of-the-office. This confirms that Pete is working with the hacker to steal money from Joe and his customers.
● Users > Hacker > Downloads > The hacker downloaded Ophcrack. This is a Windows password cracker, and the hacker can attempt to use it to hack into other users’ accounts on the computer. It is possible they could have used it to hack into Jane Smith’s account. Since Jane’s account initially had administrative privileges, it is possible the attacker could have used Jane’s account to give the “Hacker” account administrative privileges.
● Users > Hacker > Downloads > The hacker downloaded Mimikatz. Mimikatz is an open-source application that allows users to view and save authentication credentials such as Kerberos tickets. This can be used by the hacker to gather credentials on Joe’s PC.
7. Project Completion
Take the following steps when you are done answering the challenges and securing Joe’s PC:
● Save your answer template as both a Word document and PDF. Make sure your name and date are on it.
● Shutdown the virtual Windows 10 PC.
● Submit the PDF to Udacity for review.
