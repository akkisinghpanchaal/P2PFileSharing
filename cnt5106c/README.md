Computer Networks (CNT5106C UF) Course Project - Fall 2020

1. Build a P2P file-sharing application similar to BitTorrent protocol in Java.
2. File distribution with choking and unchoking mechanism among peers using TCP (reliable transport layer protocol).
3. Group Number: 12 
4. Group members: 
   (i) Kratika Singhal, UF ID:6953-5971
   (ii) Suprith Reddy Gurudu, UF ID:9961-2134
   (iii) Akshay Kumar, UF ID:4679-9946

How to execute the project:
1. open the terminal (in lin114-00 to lin114-08 lab servers)
2. change the directory to the project folder
3. run the 'make' command as shown below (compiles java files and creates class files)
	>> make
4. run the below command to start the remote peers
	>> java RemotePeerInitiator

Note: If the above command does not work, i.e., unable to start peers, we need to start the peers manually each in separate terminal as shown below
>> java peerProcess PeerID
	
PeerID ranges from 1001 to 1009 in this context of configuration files

Please find the log files in the 'logs' folder.  

Project demonstration video can be found here: 
https://uflorida-my.sharepoint.com/personal/sgurudu_ufl_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsgurudu%5Fufl%5Fedu%2FDocuments%2FCN%20Project%20Fall%202020%20G12%2FFinal%20Project%20Vid%20v3%2Emp4&parent=%2Fpersonal%2Fsgurudu%5Fufl%5Fedu%2FDocuments%2FCN%20Project%20Fall%202020%20G12&originalPath=aHR0cHM6Ly91ZmxvcmlkYS1teS5zaGFyZXBvaW50LmNvbS86djovZy9wZXJzb25hbC9zZ3VydWR1X3VmbF9lZHUvRVZNYlFpRTRMb3hHdE1DN2lxWkxQMHdCOU5jY1VEOUNHeFhiaVF2TkMtdUhYZz9ydGltZT0xUGVwYm1TZTJFZw

