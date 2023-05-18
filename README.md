<p align="center">
 <img src="https://i.imgur.com/eNtgoKd.jpg" height="80%" width="80%" alt="lsp"/>
</p>

<h1>Manage Account Policies</h1>


<h2>Description</h2>

Prepare yourself for an exhilarating expedition into the realm of Windows administration! As a Windows administrator, you hold the key to safeguarding precious data, fortifying system integrity, neutralizing vulnerabilities, and achieving a harmonious balance between security and user productivity. In today's demonstration we are going to be configuring specific password and account lockout policies using the Local Security Policy in Windows.

Let's dive into the exciting realm of password and account lockout policy configurations! Here's what we are configuring:

Password Settings: 
    Cycle through 10 passwords before reusing an old one.
    Change the password every 90 days.
    Keep the password for a minimum of 14 days.
    Create a password that is at least 8 characters long.
    Craft a password that meets complexity requirements, including uppercase letters, lowercase letters, numbers, or symbols.

    

Account Lockout Policies: 
    Lock out any user who enters five incorrect passwords.
    Automatically unlock an account after 60 minutes.
    Set a 10-minute waiting period after a failed logon attempt.

    

<br />

<h2>Environments Used </h2>

 <b>Windows 10 </b> <p>


<h2>Program walk-through:</h2>

<p align="center">
Select Start and then select Windows Administrative Tools > Local Security Policy.

<br/>
<img src="https://i.imgur.com/2pESE6D.png" height="80%" width="80%" alt="lsp"/>
<br />
<br />
From the left pane, expand and select Account Policies > Password Policy.
 <br/>
<img src="https://i.imgur.com/dZB7jdd.png" height="80%" width="80%" alt="lsp"/>
<br />
<br />
 From the middle pane, double-click the applicable policy to be modified.   Configure password settings:
        Cycle through 10 passwords before reusing an old one.
        Change the password every 90 days.
        Keep the password at least 14 days.
        Create a password at least 8 characters long.


 <br/>
<img src="https://i.imgur.com/Ny5DdEf.png" height="80%" width="80%" alt="lsp"/>
<br />
<br />
 Don't forget, we are also creating a password that meets complexity requirements such as using uppercase letters, lowercase letters, numbers, or symbols. Make sure to Enable and press Ok.

 <br/>
<img src="https://i.imgur.com/5jAXrVZ.png" height="80%" width="80%" alt="lsp"/>
<br />
<br />
 Configure the account lockout policy to:
        Lock out any user who enters five incorrect passwords.
        Unlock an account automatically after 60 minutes.
        Configure the number of minutes that must elapse after a failed logon attempt to 10 minutes. That's it we are finished.

<br/>
<img src="https://i.imgur.com/AOeh33N.png" height="80%" width="80%" alt="lsp"/>
<br />
<br />
I hope you enjoyed this demonstration.

 <br/>
<img src="https://i.imgur.com/60ohKCC.jpg" height="80%" width="80%" alt="lsp"/>
<br />
<br />



</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
