9# computation-mapping #
# **COMPUTATION** 
+ **HOST**
    - IT IS A BARE METAL. IT IS A HARDWARE THAT IS CONNECTED TO ANY NETWORK ( Server  with no. OS)
 
+ **VIRTUAL MACHINE(VM)**

   - IT USES SOFTWAER INSTEAD OF PHYSICAL COMPUTER TO RUN PROGRAMS AND DEPLOY APPS.
 + **CONTAINER**
    -DOCKER, LXC, KAAS, IAAS
    - ORCHE STORAGE- KUBERNETS, DOCKER SWARM, MEESOS, EKSCOS
      
 + **COMPUTATION UNITS**
     - CPU(ALU), DPU, GPU, SOC, FPGA, ASICS, FAB
     - GRAPHINE OS, BHAR OS
       
     1. **GPU**     
            - SILICON, PHOTONIC
      2. **DPU**
            - RISC-V
       3. **CPU**
             - X-86, RISC-V
       5. **PHOTONIC**
             - PHOTONS, PRNG, QRNG,QC
       7. **FAB**
            - AMD, INTEL, SAMSUNG
 
  + **COMPUTER OPERATING SYSTEM**
        
    1. **KERNEL SPACE**
        - It acts as a bridge between applications and data processing done at the hardware level. It is the central component of an OS.
        - HUGE PAGES,FMS,SCHEDULE, ETC            
         
    2. **USER SPACE**
         - User space usually refers to the various programs and libraries that the operating system uses to interact with the kernel.
    3. **GRAPHINE OS**
          - GrapheneOS is an Android-based, open source, privacy and security-focused mobile operating system for selected Google Pixel smartphones
    5. **BHAR OS**           

   # **NETWORKING**
   + **OPEN SYSTEMS INTERCONNECTION (OSI) LAYER**
         - PHYSICAL, DATA LINK, NETWORK, TRANSPORT, SESSION, PRESENTATION, AND APPLICATION
                
   + **SWITCH**

     - IT IS A HARDWARE THAT CONNECTS DEVICES ON A COMPUTER NETWORK BY USING PACKET SWITCHINNG TO RECIEVE AND FORWARD  DATA TO DESTINATION DEVICE.
   
    
+ **ROUTER**
    
+ **CNI**

    1. **CELIUM**
    2. **CALICO**

  + **VIRTUALIZATION**

     1. OPEN VIRTUAL SWITCH(OVS)
     2. VECTOR PACKET PROCESSING(VPP)
   
   + **LOAD BALANCER**

        1. APPLICATION LOAD BALANCER
        2. NETWORK LOAD BALANCER
        3. CLASSIC LOAD BALANCER ( THIS IS RARELY USED)
    + **UDP PROTOCOLS**
        - IT IS A TRANSPORT LAYER PROTOCOL
        - IT IS UNREALIABLE AND CONNECTIONLESS PROTOCOL, SO THERE IS NO NEED TO ESTABLISH A CONNECTION PRIOR TO DATA TRANSFER
        - IT HELPS TO ESTABLISH LOW LATENCY AND LOSS- TOLERATING CONNECTIONS PRIOR TO DATA TRANSFER.
        - ![UDP-header](https://github.com/ManavCodingspace/computation-mapping/assets/145857624/954d1dfa-3429-4eb2-944a-38c42b98e334)
        - IMPLICATIONS USES BY UDP- + NTP (Network Time Protocol)
                                    + DNS (Domain Name Service)
                                    + BOOTP, DHCP.
                                    + NNP (Network News Protocol)
                                    + Quote of the day protocol
                                    + TFTP, RTSP, RIP.
                                   

    + **TCP PROTOCOLS**
    + **PROXY**
             - IT IS A GATEWAY BETWEEN USERS AND THE INTERNET IT IMPROVES SECURITY, PRIVACY AND PERFOMANCE.

        1. ***REVERSE PROCY SRERVER***
        2. ***WEB PROXY SERVER***
        3. ***ANONYMOUS PROXY SERVER***
        4. ***HIGHLY ANONYMITY SERVER***
        5. ***TRANSPARENT PROXY***
        6. ***CGI PROXY***
        7. ***SUFFIX PROXY***
        8. ***DISORTING PROXY***
        9. ***TOR ONION PROXY***
        10. ***12P ANONYMOUS PROXY***
        11. ***DNS PROXY***

     + **NETWORK TOPOLOGIES**
         - IT IS USED TO DESCRIBE THE ARRANGEMENTS OF VARIOUS TYPES OF TELECOMMUNICATION NETWORKS INCLUDING COMMAND AND CONTROL RADIO NETWORKS.

           ![download](https://github.com/ManavCodingspace/computation-mapping/assets/145857624/7d743089-29d4-4cfe-a289-6ef16bef281d)
      
     + ***CIDR NOTATIONS**
           - IT is a method for allocating IP addresses and for IP routing
        
        1. **CLASSES OF CIDR NOTION**

           - **CLASS A** - A Class A IPv4 address has 8 network prefix bits.
               
           - **CLASS B** -  Class B IPv4 address has 16 network prefix bits
            
           - **CLASS C** - Class C IPv4 address has 24 network prefix bits.

       + ***SUBNETTING***
           - IT IS A PRACTICE OF DIVIDING A NETWORK INTO TWO OR MORE NETWORKS.

       + ***PUBLIC NETWORK***
           - IT IMPLIES THAT EVERYONE HAS THE ACCESS AND THROUGH IT CAN CONNECT TO OTHER NETWORKS OR THE INTERNET

       + ***PRIVATE NETWORK***

       + ***STATIC IPs***
            - which means it stays same over the time

       + ***DYNAMIC IPS***
            - WHICH MEANS ADDRESS CAN CHANGE OVER THE TIME.

       +  ***FIREWAll***
              - IT IS A NETWORK SECURITY SYSTEM THAT MONITORS AND CONTROLS INCOMING AND OUTGOING NETWORK TRAFFIC BASED  ON PREDETERMINED SECURITYV RULES.
       +  ***PUBLIC DNS***
       +  ***PRIVATE DNS***
       +  ***VPN***
          - IT CREATES A SECURE  CONNECTION BETWEEN A COMPUTING DEVICES AND COMPUTER NETWORKS
  
       +  ***IPv4***
       +  ***IPv6***              
       + ***NAT***

  # **STORAGE**
  + **CEPH**
     - IT PROVIDES OBJECT STORAGE, BLOCK STORAGE AND FILE STORAGE
  + **RAID**
    - IT IS A TECHNOLOGY THAT COMBINES MULTIPLE PHYSICAL DISK DRIVE INTO ONE OR MORE LOGICAL UNITS FOR THE PURPOSES OF DATA REDUNDANCY, PERFORMANCE  IMPROVEMENT, OR BOTH 
  + **NFS**
     - IT PROVIDES USERS TO ACCESS THE FILES IN THE REMOTE AREAS.
  + ***DATABASES***
      - ORGANIZED COLLECTION OF STRUCTURED INFORMATION, DATA.
  + ***KEY VALUE STORES***
         - IT PROVIDE SUPPORT FOR DEFINED DATA TYPES LIKE INTEGERS AND TEXT
  + ***RACKS***
      - FRAMEWORK FOR HOLDING, CARRYING, OR DISPLAYING A SPECIFIC LOAD OR OBJECT.
  + ***DATA CENTERS***

      a.***HYPERSCALING***

    2. ***HCL***

    3. ***PRIVATE***

    4. ***PUBLIC CLOUD***
    + ***DISC IOPS***
           - IT IS INPUT/OUTPUT PERFORMACE MEASUREMENT USE TO CHARACTERIZE COMPUTER STORAGE DEVICES.
 
# **SECURITY**
1. **SSL CERTIFICATE**
       - IT IS A CERTIFICATE WHICH ENABLE A WEBSITE TO  USE HTTPS
2. **PKI INFRASTRUCTURE**
        - IT IS A GOVERING BODY BEHIND ISSUING  DIGITAL CERTIFIACTES
        - HELPS TO PROTECT CONFIDENTIAL DATA AND GIVES UNIQUE IDENTIES TO USER AND SYSTEM. THUS IT ENSURES SECRUITY IN COMMUNICATIONS.
        - a. **CERTIFICTE AUTHORITHY**
          b. **REGISTRATION AUTHORITHY**
          c. **CERTIFICATION DATABASE**
          d. **CENTRAL DIRECTORY**
          e. **CERTIFICATE MANAGEMENT SYSTEM**
          F. **CERTIFICATE POLICY**
       
3. **ZERO TRUST SECURITY**
     - security model that requires strict identity verification for every person and device trying to access resources on a private network, regardless of 
       whether they are sitting within or outside of the network perimeter              
   A. TECHNOLOGY USE IN IT IS ZTNA              

        ![download](https://github.com/ManavCodingspace/computation-mapping/assets/145857624/2a7459d4-0eaf-4459-943e-5aba9e2de2ab)

4. **PASSWORD/SECRET ROTATION**
5. **SITE-TO-SITE VPN**
6. **CLIENT-TO-SITE VPN**
     
# **LOAD BALANCER**
   - IT IS A METHOD OF DISTRIBUTING NETWORK TRAFFIC EQUALLY ACROSS POOL OF RESOURCES THTA SUPPORTS AN APPLICATION    
    ![download](https://github.com/ManavCodingspace/computation-mapping/assets/145857624/559adfab-7b41-48dc-9c3d-8d7d81a55615)

 1. **L4 LOADBALANCER**
        - MANAGES TRAFFIC BASED ON NETWORK INFORMATION SUCH AS PROTOCOLS AND APPLICATIONS PORTS WITHOUT REQURING VISIBILITY INTO ACTUAL CONTENT OF MSG.
        - EFFECTIVE FOR SIMPLE LOADBALANCING AT THE PACKET LEVEL. Messages can be forwarded efficiently, quickly, and securely because they are neither decrypted nor inspected.
        - + **UDP PROTOCOLS**
        - + **TCP PROTOCOLS**  
 3. **L7 LOADBALANCER**
     
               

   
 

   
