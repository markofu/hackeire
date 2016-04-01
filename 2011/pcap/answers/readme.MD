| Number        | Question      | Answer        | Score |
| :-------------: | :-------------: | :-------------: | :-------------: |
| 1(a) | What was the complete URI of the original web request that led to the client being compromised? | http://10.20.0.111:8080/banking.htm | 1 |
| 1(b) | What file type was requested in the final web request to the malicious server? (Answer a, b, c ,d or e) <ul><li>a. windows executable</li><li>b. javascript</li><li>c. pdf</li><li>d.word document</li><li>e. gif | e | 2 |
| 1(c) | What was the complete URI of the original web request that led to the client being compromised? | ea7df583983133b62712b5e73bffbcd45cc53736 | 2 |
| 1(d) | What is the number of the first frame that indicates that the client has been compromised? | 4722 | 3 |
| 1(e) | At one point, the malicious server sends a malicious file to the client. What type of file is ? (Answer a, b, c ,d or e) <ul><li>a. windows executable</li><li>b. javascript</li><li>c. pdf</li><li>d. worddocument</li><li>e. gif</li></ul> | a | 2 |
| 1(f) | What is the sha1 hash of the malicious file? | 94adf100411a80076192766a214e0ff92da13ab7 | 2 |
| 1(g) | What vulnerable software is exploited (in the following format, ff3.5, ff3.6, Word2010, ie7, Safari2, Chrome2, AdobeReader, ie9)? | 2 |
| 1(h) | When the capture ends, is the client still connected to the malicious attacker? Answer either "yes" or "no". | yes | 2 |
| 1(i) | Can you give the correspondingCVE security bulletin that covers the vulnerability here that was exploited (answer in form of CVE-$year-$number)? | CVE-2010-0249 | 2 |
| 1(j) |  From the capture, it is clear that the attacker gets a certain form of access (i.e. the interface), what (type of) access does the attacker "get" on the client? | shell | 2 |
| #### | #### | #### | #### |
| 2(a) | What is the frame that indicates the something strange might be going on? | 8 | 2 |
| 2(b) | What tool is generating this traffic? | nmap | 1 |
| 2(c) | What does this frame constitute the beginning of? (Answer a,b,c,d or e) <ul><li>a. TCP Scan</li><li>b. Ack Scan</li><li>c. Xmas Scan</li><li>d. Ping Scan</li><li>e. Syn Flood</li></ul> | 8 | 1 |
| 2(d) | The 'miscreant' then runs two scans beginning just after six minutes and 24 minutes into the trace, however, these traces weren't to his/her liking as they were too slow. On the following scans, a switch was removed from the command to improve the speed, what was this switch (just the letters, case-sensitive)?  | sU | 3 |
| 2(e) | What switch was added to the final scan (case-sensitive)? | A | 3 |
| #### | #### | #### | #### |
| 3(a) | What type of ICMP traffic is this? (Answer a, b, c ,d or e) | <ul><li>a. Echo request/reply</li><li>b. OS Mapping</li><li>c. Covert Channel</li><li>d. Inverse Mapping</li><li>e. Route Redirect</li></ul> | c | 1 |
| 3(b) | What is the number of the first frame that indicates that something funny might be going on? | 15 | 2 |
| 3(c) | What tool generated this 'malicious' traffic? | ptunnel | 1 |
| 3(d) | What is the application layer protocol that is hidden within the ICMP traffic (i.e. the payload)? | ssh | 1 |
| 3(e) | What is the 'true' destination of the ICMP traffic generated from 192.168.5.208? | 172.16.15.138 | 3 |
| 3(f) | What is the session identifier for each packet (answer in hex (2 bytes), i.e inf the format of 1111)? | e59c | 1 |
