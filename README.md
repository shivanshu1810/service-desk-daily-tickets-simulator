# Service Desk Daily Tickets Simulator

I practice service desk tickets every day on a simulator website to keep my skills sharp. This repo is my daily log. I write what the problem was and how I fixed it.

## November 6, 2026

I closed 5 tickets and got 82 points.

1. A user PC was completely dead after a power outage. The power supply had failed. I set up a replacement PC, registered it as SD2036, and shipped it to the user with a return label. She confirmed it works.
2. A user came back from a three week vacation and her password had expired. I checked her identity first, then reset her password and sent her a temporary one.
3. A user got married and needed a name change on her account. I changed her name and email and kept the old email as an alias so no mail is lost.
4. A user said the WiFi keeps disconnecting. It was not her computer. The internet provider was down for the whole company, so I posted an announcement with the repair time so everyone knew.
5. One more ticket about the internet being down. Same provider outage, so I closed it with the announcement.

## November 8, 2026

I closed 5 more tickets and got 77 points. I now have 159 points in total and a Bronze rank. I have closed 10 tickets so far.

1. CRITICAL. The internet was completely down for one user and she could not work. I checked the provider in the server room. The provider was down for the whole company with a 45 minute repair time, so I posted an announcement in the company chat with the repair time. +5 points.
2. CRITICAL. Nobody on the 3rd floor had internet. This one was different. The floor switch was in an error state, so I rebooted it and the internet came back in about 45 seconds. The user confirmed the floor was back online. +30 points.
3. A user's WiFi kept disconnecting every few seconds. It was the same provider outage as the first ticket, so the announcement covered it and the ticket closed. +5 points.
4. A remote worker's VPN disconnected and would not reconnect. I remoted into her computer, flushed the DNS, restarted the computer, and reconnected the VPN. The tunnel came up active. +15 points.
5. A remote worker could not get to her files on the shared drive. Her VPN was disconnected. I connected the VPN and checked the drive in File Explorer. The folders were all there, so no re-mapping was needed. +22 points.

There were 5 more tickets waiting in my queue (a wrong computer clock, office printers down, a new employee account setup, and two more). The free plan gives me 5 tickets a day, so those waited for the daily reset. I closed them on November 12, below.

## November 12, 2026

I closed 5 more tickets and got 103 points. I now have 262 points in total and a Bronze rank. I have closed 15 tickets so far. I am 10 points away from the Troubleshooter rank.

1. HIGH. A user's computer clock was wrong and her meetings were off by an hour. The timezone was set to Eastern instead of Central. I changed the timezone to Central Time and synced the clock with the Internet time server. +20 points.
2. HIGH. None of the printers on one floor were working. I rebooted the print server PRINT01, waited until it came back online, and confirmed in the company chat that printing worked again. +20 points.
3. A new employee needed her account set up. I created her Directory account and added her to the Engineering, VPN-Users and CodeRepo-Access groups. +25 points.
4. An employee moved to a new team and could not open her files and folders. In the Directory I added her to the IT Infrastructure group and removed her from the Engineering group. +20 points.
5. A user's second monitor was black and showed No Signal, even though the monitor worked on a coworker's laptop. I updated the integrated graphics driver and restarted the PC, and the second monitor was detected again. +18 points.

The screenshots in this repo show my dashboard, my finished tickets, and one ticket in full detail.

These are the same day to day tasks I did as a Tier 1 Service Desk Analyst at Royal Victoria Regional Health Centre.

I will add more days as I do more tickets.
