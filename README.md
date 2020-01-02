# omv5raspi4file

So it all started with a project on the Facebook Page of Raspberry pi projects
https://www.facebook.com/groups/RaspberryPiProjects/

since having a raspberry pi 1 iv bought every pi going, (cheap as chips £35UK). im slowly building and learning myself as i go along.

I have always wanted to build my own little NAS sever so i can access it on the go. Mainly my work files so i can easily access them where ever i am in England.

I was researching for a while how to setup my own NAS that would work with the NEW RPI4. Loads and loads of videos out there on how to set it up. So i bought all the componants that i required, and over the Chirstmas period(2019) i did just that, set it up, with old drives, bought new ones and upgraded again and again until now. Where the RPI4 is running brilliant! One of the users in the Raspberry pi projects advised why dont i upload my work so its fully setup for everyone else to access. So here it is.

I have gone thought countless hours of installations of RPI4/OMV5 to get it running, pretty well. Iv cloned my drive and uploaded it to a torrenting factor so its accessable to everyone with very little effort. On the image that i have uploaded it comes with pree installed docker/portainer and cocker, fully working without any issues. the only commands you will have to carry out is the dnchcd.conf to adjust your isp to set it to a dedicated ip of your choise.

Once the img file has downloaded, set your isp ip to your choise either dynamic or static(if it is dynamic reserve a slot on your router to prevent it changing the ip of the rpi5omv)

carry out sudo command of

sudo nano /etc/dhcpcd.conf

scroll down the page file untill you see interface eth0 and adjust your settings accordingly

All usernames and passwords are
user: admin
pass: adminadmin

the raspberrypi user and passwords are
user:pi
pass:adminadmin


i will be posting updated images of the RPI4OMV5 so it is alot easier for everyone else.
