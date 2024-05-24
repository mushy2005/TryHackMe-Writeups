# Anthem
Exploit a Windows machine in this beginner level challenge

## Steps
1. First and foremost, we need to spin up the target machine. Do take note of the IP address as that'll be useful.
2. The very first thing we should do, as it states on THM's website, to run nmap and see what ports are open. The command would be `nmap (IP address)`. Give it a few seconds and you'll see something like below:

![Nmap](./images/anthem1.png "Nmap Result") <br>

3. As we can see, we have two ports open. Now, using what we see, we need to answer the following question: "What port is for the web server?". This would be port 80, as that's the HTTP service.
4. Next question: "What port is for remote desktop service?" This would be port 3389, as that's the RDP port.
5. When we access the site, it'll look something like this:

![]()

