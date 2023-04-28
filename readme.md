Exercises:
1)	Prepare a rule-profile to allow all traffic for TCP protocol and block every other kind of traffic.
2)	Prepare a rule-profile to allow only TCP port 80 and 443 traffic and block every other kind of traffic.
3)	Prepare a rule-profile to implement whitelist like module so it will allow every traffic on following websites/IPs. (Note. You need to add DNS rule to allow DNS resolution for all queries)
  a.	178.236.7.18
  b.	172.65.64.50
  c.	17.86.254.172
  d.	google.com
  e.	Facecbook.com
  f.	Apple.com
4)	Prepare a rule-profile to mark DSCP: 2 for ndpi chat category and mark DSCP: 1 for every other kind of traffic.
5)	Prepare a rule-profile to allow Network ndpi category, block SocialMedia and allow every other category.
6)	Prepare a rule-profile to allow only specific source devices and block traffic for all other devices.
  a.	11:22:33:44:55:66 MAC device having IP 192.168.1.2
  b.	AA:BB:CC:DD:EE:FF MAC device having any IP
  c.	192.168.1.3 IP device with ANY MAC
7)	Prepare a rule-profile to allow all traffic for devices having ACTIVE state session and for other state sessions or missing sessions allow only login.com domain

Notes: 
-	Each exercise must be in separate json file.
-	Each exercise must have complete steps including rule-chains, rules, expressions etc. See. attached production example file. 
-	Each exercise must be valid in terms of simple JSON syntax rules
-	Each exercise must be valid in terms of AG Rule Engine logic. So you need to validate it either in your local AG or hyperdrive.
-	Each exercise must work in practical scenario once you configure AG Rule Engine to do so. (Please discuss this step with us before doing it)
