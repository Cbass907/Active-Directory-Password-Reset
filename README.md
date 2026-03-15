# Active-Directory-Password-Reset

![Active Directory Logo](https://github.com/Cbass907/Active-Directory-Password-Reset/blob/main/Screenshot%202026-03-14%20011854.png?raw=true)
<h1>Password Reset via Active Directory</h1>
In this tutorial, we will go through the process of changing a users' password due to lockout from several invalid attempts.

<h2>Systems and Services used</h2>

- Windows 10 Server 2022
- Windows 11 Client
- Active Directory

<h2>Password Reset Steps</h2>

- Password lockout
- User navigation through Active Directory
- Working the issue
- Resolution

<h2>Password lockout</h2>

<img src="https://github.com/Cbass907/Active-Directory-Password-Reset/blob/main/VirtualBox_Windows111_15_03_2026_01_21_31.png?raw=true.png" width="600" />
In this scenario, Jim Watkins, a fictional user in an enterprise environment, had been locked out of his account due to repeated failed login attempts. He contacts help desk support, and explains the issue.

<h2>User navigation through Active Directory</h2>

<img src="https://github.com/Cbass907/Active-Directory-Password-Reset/blob/main/VirtualBox_Windowsserver10_15_03_2026_01_15_43.png?raw=true.png" width="600" />
The help desk technician then proceeds to active directory through the domain of the company. Specifically, through active directory users and computers.

<img src="https://github.com/Cbass907/Active-Directory-Password-Reset/blob/main/VirtualBox_Windowsserver10_15_03_2026_01_24_21.png?raw=true.png" width="600" />
Under the Lab.local tree, he then right clicks on the accounts folder and right-clicks find (in an enterprise situation, this would be much faster than scrolling through all the users, assuming there could be hundreds if not thousands), and searches for Jim Watkins.
