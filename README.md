# AgentPannel
pannel for agents for managing documents


Run this for open the 80 port for out side
==========================================
iptables -I INPUT -p TCP --dport 80 -j ACCEPT

Run this to add services for mongo and web servers
==================================================
pm2 start "mongod"
pm2 start "npm start"
