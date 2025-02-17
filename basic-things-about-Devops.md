
# DevOps-by-abhishek-veeramalla

Notes about all that I have learned...

## 1) What is DevOps?
- It has a culture that improves the organizational ability to deliver the application.

## 2) Is DevOps is only about delivery?
- DevOps is a process of improving your delivery, that mean making our delivery quick by ensuring that there is a proper automation.
- You have ensured that the quality is in place.
- You have ensured that set up proper monitoring and ensured that you have a continuous testing.
- DevOps :-
    - Automation
    - Quality
    - Continuous Monitoring
    - Continuous Testing

## 3) Why DevOps?
- DevOps combines development and operations to increase the efficiency, speed and security of software development and delivery compared to traditional process.

## 4) Software Development Life Cycle(SDLC) :-
- SDLC is a process that is followed by the industry to design, develop and test the high quality product.
- Produce high quality product :-
    - Design
    - Develop
    - Test
- Standerd of SDLC :-
    - Planning -> understand the requirement of the customers.
    - Defining -> documenting the things that we want
    - Designing -> focus on high level design (HLD) and low level design (LLD).
    - Building -> development(coding) -> use central repository to store code (git).
    - Testing -> identify bugs -> quality assurance team.
    - Deploy -> push on a production server -> customer
above 6 stages are the standards of the SDLC.

- As an DEVOPS engineer out main moto is that fastens this process (building, testing and deployment).

- DEVOPS engineer would automate the process.
- In this automate process we are focusing on building, testing and deployment process.


## 5) Virtual Machine :-
-   What is Virtual Machine?
    - It is a compute resource that uses software
        insted of a physical computer to run program and deploy apps.
    - One or more Virtual "guest" machines run on a physical "host" machine.
    - each VM runs its own operating system and function separately from the other VM's.

- What does Hypervisor do?
    - Hypervisor is a software that you can use to run multiple virtual machines on a single physical machine.
    - Every VM has its own operating system and application.
    - The Hypervisor allocates the underlying physical computing resource such as CPU and memory to individual VM as required.

- [How to create aws account, create virtual machine and launch EC2 instance?](https://youtu.be/QDymcZ5xYow?si=Q92nMxRqoEkrErAh)

## 6) Steps to connect your EC2 instance with terminal :- 
- Run this command :
-> ssh ubuntu@yourPublicAddress

then it will ask for the fingerprint say 'yes', 
it will denied permission for connection beacuse you did not provide any key value pair file.

- For provide that key value pair file you need to run this command 
-> ssh -i /path of your key value pair file.pem ubuntu@yourPublicIPAddress

- If in case it gives an error(your .pem file is too open), then you need to change the permission by using below command 
-> chmod 600 /.pem file path

- Again run second command for login in virtual machine. 

## 6) Linux :- 
- Why linux OS is using in many companies?
    - linux is a free os
    - linux is very secure
    - linux is fast
    - linux provides different kinds of distribution.

- Architecture of linux OS:
    - level - 1)
        - system software
        - user process
        - companies
    - level - 2)
        - System Libraries
    - level - 3) 
        - Kernel

- What is Kernel?
    
    -> heart of your operating system
    
    -> establish the communication between your hadware and software

    -> manage devices
    
    -> memory management
    
    -> process management 

    -> handles system calls

- What is system libraries?
    
    -> Responsible for the performing the tasks 

    -> ex. libc is a system library.

- What is operating system?
    
    software <--> OS <--> hardware

    -> we use OS to establish the connection between software and hardware.
