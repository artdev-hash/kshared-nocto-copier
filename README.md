<img src="./src/assets/img/kshared-nocto-copier.png" align="center">

kshared-nocto-copier is copying shared file via command prompt

## Description

It allow's you to shared easily the shared folder in an configured open number of network computer's you have...

### Dependencies

* Windows Operating System

### Installing

* Clone or Download the Repository

### Executing the Command

* See the Full Read Me file to configure the command

* Modify / Edit the specifics of the command file...

* Test if working and when done...

* Execute or add it to scheduled specific time or date you need it to be done in windows

## Information

```
net use
```
This is to specify local drive in the network

```
f:
```
Not only f: but any letter that to be followed by semicolon as long as the drive is not use

```
\\ip
```
This is a static ip of the server or can be a machine name in the local network
192.168.254.01 is only an example static ip address..

```
\shared-name
```
This is the name of the location being shared on the server machine, user who sets up sharing will assign this

```
{password}
```
The complete highlighted term is the password of the machine

```
/user:
```
The name of the computer first then put the username of the machine...

```
/P:yes
```
This means the connection is persistent and this will keep the connection alive

```
xcopy
```
The command use for copying

```
C:\test
```
The directory folder you will copy

```
\\ip again
```
The directory of destination you will copy the file...

```
/w/f/j/s/z
```
Some code incorporated in xcopy...

## Note :

I have used this for backup and for transferring files easily in my network especially when my usb is occuppied with other things.. you can try it too from windows to linux or windows to windows its up to you.. but at your own risk.. Thank you.. :rocket: