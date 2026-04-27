Linux, Networking and Dev Basics

Till now we learned:
    Data Engineering Basics
    Data Formats

    But today we learn something every Data Engineer must know:
        Linux + Networking + Git

    Let me ask:
        where do data pipelines run ?
            On servers = and most servers use Linux

PART 1: LINUX BASICS
    Linux is an operating system used in:
        Servers
        Cloud
        Big Data Systems

    Common Linux Commands
        Check current directory
            $ pwd

            output: /home/project/devops

        List files
            $ ls

        Change Directory
            $ cd devops

            navigate to users home directory
            $ cd ~

        Create file
            $ touch file1.txt
            Note: if my current directory is devops, then file1.txt created in devops            

        Create folder in devops
            $ mkdir data


        View file
            $ cat file.txt

        Write into file
            $ echo Hello >> file.txt

        View file
            $ cat file.txt

        Delete file
            $ rm file.txt  

        Which command shows current location? pwd


    Hands-on:
        Open terminal and run:
            mkdir demo
            cd demo
            touch test.txt
            ls    

Part 2 - SSH and Ports
    SSH (Secure Shell)
        SSH is used to:
            connect to remote server

        $ ssh user@server_ip_public  

        Like remote control for computer


    Ports
        Port = Door for communication
        22 -> SSH
        80 -> HTTP
        443 -> HTTPs

        Which port is used for SSH ? 22

Part 3 : Processes vs Threads
    Programs don't run directly, they run as:
        Processes and Threads

    Process ?
        Independent program

    Thread ?
        Part of a process

    Process = Restaurant
    Threads = Waiters

    Process         Thread
    Heavy           Lightweight
    Independent     Shared

    Which is faster ? Thread

PART 4: ENVIRONMENT SETUP
    Before coding, we need environment setup
        What is Environment
            Tools + software needed

            Example
                Python
                Java
                Spark
    
    Hands-on    
        Check Python:
            python --version
        
        Learning
            Always verify setup

Part 5: GIT BASICS
    Git is used for:
        Version control (tracking code changes)

        Like saving versions of file


    Download Git and Install with default settings
        $ git --version

    Basic Commands
        git init
        git add README.md
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/itnewcon/debatch.git
        git push -u origin main        







