# Copy-Ip-address-from-PC-to-another-PC
Copy Ip address from PC to another PC

---------------
Step:1

1. run cmd as an administration
2. cd/
3. netsh -c interface dump > testip.txt
4. more testip.txt
5. exit

--------------
Step: 2

1. copy text file in "Local Disk: C"
2. Done


-----------------
Step:3

1. run cmd as an administration
2. cd/
3. netsh -f testip.txt
4. exit

----------
