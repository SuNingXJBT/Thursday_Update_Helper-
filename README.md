# Thursday_Update_Helper-
Resolve the eFootball's update issue on every Thursday.

Every Thursday, Konami will release a new live update. But not all the players can update
successfully. Some will struggle with this issue. This article will help them to resolve it.

# What happens with the live update

1.This domain is used for live update.  d1ln4m3c7n87ju.cloudfront.net

2.The downloaded files are stored in a hidden directory C:\programdata\Konami

3.There are at least 16 servers IP working with that domain. The DNS will change every few minutes, and 4 of them are active at the same time .

4.Not all connections to the servers are stable. If player’s ISP has high packet loss rate for the connection , the update will fail. Wait couple minutes, till DNS return new batch of better IPs, the update will succeed.

5.The connection to update server is HTTP. Player may use proxy or VPN to get better connection and resolve the issue.

6.Deleted the hidden directory C:\programdata\Konami will trigger a new downloading process.  Player may also press “through pass” button on the game’s startup screen to delete files. 

7.But this simple method still depends on luck. 


# 2.Resolution 
# 2.1 Manually Method
Use tool to check all the connection to update servers. Choose the most stable one. If there is none stable connection, you have to use VPN or proxy for update. 

Rewrite the DNS result for d1ln4m3c7n87ju.cloudfront.net . Make sure the best IP is chosen.

Method 1: Rewrite the C:\Windows\System32\drivers\etc\hosts file , for example:

3.163.128.31 d1ln4m3c7n87ju.cloudfront.net

Method 2: Or use Adguard-dns home to rewrite DNS

# 2.2 Live update helper tool 

This eFootball_liveUpdateHelper tool is shared in group : https://t.me/eFootballxjbt

published link: https://t.me/efootballCheaterReport/198

Run this tool as administrator. It will do all the manual steps. Rewrite the hosts file. Delete the hidden directory if needed.
