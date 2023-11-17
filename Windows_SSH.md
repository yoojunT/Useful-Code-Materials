# How to SSH into Windows from Windows (and copy files remotely)

**Video Reference**
> [Start-Service sshd](https://www.youtube.com/watch?v=pFTC4Rt-EDQ) 
<br>

**Run ssh on windows**
> Start-Service sshd
> 
> Set-Service -Name sshd -StartupType 'Automatic'
<br>

**Access to File**
> ssh Administrator@<IP Address>
> 
> exit
<br>

**Copy/paste**
> scp Administrator@<IP Address>:<File_Path> Desktop 
