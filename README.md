# DNS-Cache-NetfilterQueue
<p>fix code from python2.7 to python3.6</p>
<p>original code from here:<a href="https://github.com/ShanjinurIslam/Computer-Security-DNS-Cache-Poisoning">DNS-Cache-Poisoning</a></p>
<p>before runnig this you need apply this the firewall</p>
<p>"sudo iptables -A INPUT --dst <strong>"setipnet"</strong>/24 -p udp --sport 53 -j NFQUEUE --queue-num 1"</p>
<p>&nbsp;</p>
