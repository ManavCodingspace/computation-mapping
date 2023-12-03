# computation-mapping #
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
        - IMPLICATIONS USES BY UDP-
           + NTP (Network Time Protocol)

             + DNS (Domain Name Service)

                + BOOTP, DHCP.

                    + NNP (Network News Protocol)

                       + Quote of the day protocol

                          + TFTP, RTSP, RIP.
                                   

    + **TCP PROTOCOLS**
        - IT IS ONE OF THE MAIN PROTOCOLS OF THE INTERNET PROTOCOL SUITS
        - IT LIES BETWEEN THE APPLICATION AND NETWORK LAYER
        - IT IS  A CONNECTION-ORIENTIED PROTOCOL FOR COMMUNICATIONS WHICH HELPS IN EXCHANGE OF MESSAGES BETWEEN DIFFERENT DEVICES OVER NETWORK.
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
7. **ENCRYPTION**
        - It is a practice of encoding an original messsage into an uninelligable form
8. **Encryption at rest**
      -  the encryption applied to the stored data. Encryption may be implemented at the source, where data is generated and stored at the origin.
9. **End to End Encryption**
          -he combination of the encryption at rest and encryption in transit. When the data is generated at the source, it is already stored in an encrypted form.
10. **End to End transit**
       - encrypting data that is transferred between two nodes of the network. The data may be stored in an unencrypted form at the source and destination storage systems.       
# **LOAD BALANCER**
   - IT IS A METHOD OF DISTRIBUTING NETWORK TRAFFIC EQUALLY ACROSS POOL OF RESOURCES THTA SUPPORTS AN APPLICATION    
    ![download](https://github.com/ManavCodingspace/computation-mapping/assets/145857624/559adfab-7b41-48dc-9c3d-8d7d81a55615)

 1. **L4 LOADBALANCER**

    - MANAGES TRAFFIC BASED ON NETWORK INFORMATION SUCH AS PROTOCOLS AND APPLICATIONS PORTS WITHOUT REQURING VISIBILITY INTO ACTUAL CONTENT OF MSG.

    - EFFECTIVE FOR SIMPLE LOADBALANCING AT THE PACKET LEVEL. Messages can be forwarded efficiently, quickly, and securely because they are neither decrypted nor inspected.

        - + **UDP PROTOCOLS**

        - + **TCP PROTOCOLS**  
 3. **L7 LOADBALANCER**
     - IT OPERATES AT APPLICATION LEVEL
     - IT USE PROTOCOLS LIKE HTTP AND SMTP TO MAKE DESICION BASED ON ACTUAL CONTENT OF MESSAGE
     - IT TERMINATES THE NETWORK TRAFFIC, PERFORM DECRYPTION AS NEEDED, INSPECT MESSAGES, MAKES CONTENT-BASED ROUTINE DESCIONS, INTITATES A NEW TCP CONNECTION TO THE APPROPRIATE UPSTREAM SERVER, AND WRITE THE REQUEST TO THE SERVER.
               
# **AWS**
# **AWS KEYWORDS**
1.**Anamoly Detection**
    - Anomaly detection identifies suspicious activity that falls outside of your established normal patterns of behavior. A solution protects your system in real-time from instances that could result in significant financial losses, data breaches, and other harmful events.

2. **Amazon Cloudwatch**
       - it is a service that monitors application, responds to performance changes, optimizes resource  use, and provides insights into operational health.

 3. **S3**
      - it is ana object storage service offering industry-leading scalability, data availability, security, and performance.
 
 # **Computer Architectures**:

1.CISC (Complex Instruction Set Computer): A computer architecture with a diverse and extensive set of instructions, which can make it more versatile but sometimes less efficient.

2.RISC (Reduced Instruction Set Computer): A computer architecture that uses a simplified and optimized set of instructions to improve performance.

3.RISC-V (Open Source RISC Variant): An open-source RISC architecture, allowing for customization and flexibility.

4.Embedded Systems: Computer systems integrated into devices or machines for dedicated functions, such as IoT devices and industrial controllers.

5.Firmware: Firmware is like the DNA of a device. It's software permanently programmed into hardware, like the instructions for your TV remote.
         + Bucket ACLs
         + OBJECT ACLs
6.Von Neumann vs. Harvard Architecture: Two distinct computer architectural models, with Von Neumann using a unified memory space for data and instructions and Harvard using separate memory spaces for instructions and data.

7.FPGA (Field-Programmable Gate Array): Hardware that can be configured and reconfigured for specific tasks, often used in custom computing solutions.

8.ASICs (Application-Specific Integrated Circuits): Custom-designed integrated circuits optimized for specific functions or applications.         
   
# **Commonly Used Linux Commands**:
A set of essential commands for file and directory operations, file permissions, system information, text processing, package management, and process management in a Linux environment.
File and Directory Operations:

    ls: List directory contents
    cd: Change directory
    pwd: Print working directory
    mkdir: Make a new directory
    rm: Remove files or directories
    mv: Move or rename files or directories
    cp: Copy files or directories

1.***File Permissions***:

    chmod: Change file permissions
    chown: Change file or directory ownership

2.***System Information***:

    top: Display system processes
    df: Display disk space usage
    du: Estimate file and directory space usage
     free: Display amount of free and used memory in the system

3.***Text Processing***:

    cat: Concatenate and display file content
    grep: Search text using patterns
    sed: Stream editor for text manipulation
    awk: Text processing tool for data extraction

4.***Package Management (Debian/Ubuntu)***:

    apt-get: APT package handling utility (Debian/Ubuntu)
      Package Management (Red Hat/CentOS):

     yum: Package manager (Red Hat/CentOS)

5.***Process Management***:

    ps: Display information about running processes
    kill: Terminate processes by process ID 

   
