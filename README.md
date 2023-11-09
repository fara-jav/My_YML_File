# MY_YML_FILE


***!! FOR EDUCATIONAL PURPOSE ONLY !!***

## SET UP

My docker-compose.yml file for educational purpose

Downloaded Oracle VM virtual Box

Downloaded Kali Linux from [here](https://www.kali.org/get-kali/#kali-virtual-machines)

Then upload the Kali Linux to your Virtual Box

In Kali Linux, Open terminal and download Docker from [here](https://www.kali.org/docs/containers/installing-docker-on-kali/)

Download Docker-compose to run docker-compose.yml file, use [the referenece page](https://docs.docker.com/compose/install/linux/)

Import the docker-compose file from this repository.

Check out my youtube channel for videos of the exploits, [Video-cve-2019-6340](https://youtu.be/cwidnc2bmRE?si=5HTmwE9flUTuSxeR)

or see below for images of the exploit.

## EXPLOIT 1 

### Tomcat ghostcat vulnerability

Use container with tomcat from my docker-compose file 

![Screenshot 2023-11-08 224652-1](https://github.com/fara-jav/My_YML_File/assets/149855687/284b309e-07e4-4d7f-94a8-9c29e5c95deb)

Open Metasploit, msfconsole 

Search tomcat jserv

![Screenshot 2023-11-08 224915](https://github.com/fara-jav/My_YML_File/assets/149855687/64f82e1e-3312-4146-bc40-c9e312943dfe)

Next, check and configure options, then run the exploit as shown below 

![Screenshot 2023-11-08 225034](https://github.com/fara-jav/My_YML_File/assets/149855687/19467679-b91c-40b9-9123-51d937921938)

The following image shows the successful exploit by accessing the file from tomcat 

![Screenshot 2023-11-08 225110](https://github.com/fara-jav/My_YML_File/assets/149855687/e3f3c4ac-0572-4bc7-97c7-702588eb595d)



