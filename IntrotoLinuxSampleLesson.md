## Unit 3 Day 1: Introduction to Linux

### Overview

Today's class will introduce students to the fundamentals of the Linux operating system. This overview will explore the ubiquity of Linux in the tech and cybersecurity world and then dive into technical aspects like distributions and access control. Students will also refresh their terminal skills before learning how to inspect and set file permissions on the command line. 

### Class Objectives

By the end of class today, students will be able to:

* Define Linux, identify distributions, and explain how pervasive Linux is in the tech and cybersecurity field.

* Run Linux on a non-Linux operating system via a virtual machine.

* Execute basic command line functions: `ls`, `cd`, `touch`, `cp`, and `makedir`. 

* Explain the value of access controls and file permissions when working on an open source system.

* Set access control and inspect file permissions using the `chmod`, `su`, `sudo` and `chown` commands. 

### Instructor Notes

* Today's class begins a three week timeline that will cover many aspects of Linux. The knowledge and skills learned today are foundational to future classes. Like many of the skills taught throughout the curriculum, Linux will take some time getting used to. Reinforce to your students that continued practice will lead to familiarity and then competency. 

* The content of today's class is as much conecptual as it is technical. Even if students have never heard of Linux before today, they should leave with an understanding of how important and present it is in everyday life. If applicable, throughout the class, provide examples of how you have used linux in previous jobs. 

* Be aware that today's class requires downloading a virtual machine. We will walk through the steps in class

* Today's exercises will also reinforce what students learned in the previous terminal unit. Remind students that while they are learning new skills, this lesson is also an opportunity to strengthen their existing command line skills.

------

### 1. Direct Instruction: Introduction to Linux (Formal Lecture/Facilitated Discussion) (0:10)

Welcome students back to class and inform them that today's lesson will introduce the Linux operating system. 
To begin, ask students to define an operating system and provide any examples they know of. Arrive at the conclusion that:
- An operating system, or an OS,  is  the software that supports a computer's fundamental functions. It manages the resources of the system like processor, memory, disk space. It allows the computer to interact with the user. It communicates with the hardware. It executes applications, etc.
- Some popular operating Systems are: Microsoft Windows and Mac OSX
- Explain that those OS's are built on Unix. They are proprietary, meaning we as users do not have 100% insight into the minutia of the  system's specs and how they work. In other words, they are inaccessible.

[OSimage](OSImage.png)

Introduce Linux as an alternative  to these Unix systems. Explain that:

- Linux is a free, open-sourced operating system. 
- Linux provides more customization and flexibility for specific requirements of complex job functions. 
- Since Linux is free and open sourced, there are various modified versions available, known as **distributions**. 
    
    - Developers make different distributions that function better for different tasks.
    
    - Let students know that an important distribution for cybersecurity is called **Kali Linux**. It  is designed and maintained by Offensive Security, a provider of information security training.  It is optimal for digital forensics and penetration testing (a topic that we will explore in future units). 
    
    - For this sample lesson, we will work in **Ubuntu**. It is a very common and simple version of Linux that is suited well for beginners.  
    - Explain that even though there are many different distributions, we will be covering the basics today. These basics are universal amongst all major Linux distributions. (So what you learn today in Ubunto will be applicable if you work with Kali down the line.)
    
- Working in Linux will require working with the command line. Advise students that we will be refreshing our command skills in a coming exercise. 

- Explain that Linux is fundamental to the tech world and more specifically to the cybersecurity field. Tell student that they may be surprised by how many companies, applications, and gadgets are built on Linux. But we will let them see for themselves.

    - In the next exercise, students will gain an understanding of the ubiquity of Linux and its importance in the cybersecurity job market.


### 2. Guided Practice - The Ubiquity of Linux (Google it!)  (0:15) 

This exercise is designed to introduce students to the pervasiveness and importance of Linux in the world-at-large and  specifically in the cybersecurity job market. 

In this activity, students will pair up and research common everyday gadgets, companies, software etc. that utilize Linux. Then  they will research the cybersecurity job markets for positions that require strong Linux skills. 

- Send students the following file. 

- [File](Instructions.md)

- Instructions: 

    - In this activity, you will pair up with a partner and research Linux's presence in the world-at-large and in the cybersecurity field. 
    
    - First, using google, research common gadgets, compaines, software, etc. that are built on Linux. 
    
    - Find at least 10 examples and try to be as diverse as possible in your selection. 
    
    - Using popular job aggregation websites like [Indeed](indeed.com), [Glassdoor](Glassdoor), [ZipRecruiter](Ziprecruiter.com), or other research tools, search for cybersecurity jobs that require strong Linux is a key skill. 

    - Find at least 10 jobs that require Linux. Try to be as diverse as possible in your selection. 

    - As you start finding jobs, answer the following questions: 
        - Which job titles reoccur the most?
        - Do these postings mention specific distributions? Provide your best reasoning for why or why not?
        - Are any other skills mentioned or associated with Linux. 
            - For example: "Applicants must know Linux in order to complete _job functions x, y, z_. 

Monitor the class and address and complications that arise. 

### 3. Direct Instruction: Review Ubiquity of Linux (0:10) (Clock = 0:35)

Call attention back to the front of the class and begin reviewing the students' findings. 

- Call on the first student to provide some of their results. 

- After that student speaks, have them call on another student to give their findings. Write each job or product on the board as students call them out. Continue this process until you cover a variety of results. 

- Some interesting examples you can mention if there aren't already listed: NASA, Game consoles like Steam, the CERN Large Hadron Collider, Roku,  Smart Appliances, The New York Stock Exchange, the U.S. Department of Defense.

- Then, using the list of jobs, review the additional questions:  
    - Which job titles reoccur the most?
    - Do these postings mention specific distributions? Provide your best reasoning for why or why not?
    - Are any other skills mentioned or associated with Linux. 
        - For example: "Applicants must know Linux in order to complete _job functions x, y, z_. 

- If applicable, explain how you have used Linux in previous jobs or in your everyday life. 

Now that students have a conceptual understanding of Linux, we will now walk-thru how to use this operating system even though we are already using the existing operating system of the students' computers. 

[LinuxEverywhere](linuxeverywhere.png)

### 4. Guided Practice: Installing VM and Linux (0:15) (Clock = 0:50)

Now that students have a grasp of Linux, we can start using it. But first, we have to download it. 

- Explain to students that instead of uninstalling Windows or Mac and then installing Linux, we can run Linux on a simulated computer within our Mac or Windows OS, known as a **virtual machine**.

- In this activity, students will first install a virtual machine and then install the Ubuntu distribution of Linux. 

- Send students the following file. 

- [File](Instructions.md)

- Instructions: 
    - In this activity, you will install a virtual machine and then install the Ubunto distribution of Linux.
    - Your instructor will walk-thru the process with you. Follow these steps as your instructor moves along: 
    
    1. To begin, navigate to [VMWare](my.vmware.com) in your web browser.
        - Go to downloads. 
        - Select VMware Workstation 15 and follow the on screen wizard instructions. 
        - Before running virtual machine, we need to download Linux. 
        
    2.  Navigate to [Ubuntu](website)
        - Find the downloads. 
        - Choose version: Ubuntu Desktop 18.04 LTS
        
    3. Create a virtual machine using VMWare.
        - Install disc image file and select Ubunto.iso. 
        - Pick user name and set password. 
        
    - Once you are finished, you are ready to begin working in Linux. 
    
Make sure all students are running Linux on their virtual machine before moving on. 

### 5. Direct Instruction: Review Installation and Explore Linux (0:10) (Clock = 1:00)

[ubunto](ubunto.png)

All students should now be running Linux on VMware. Spend this review time to explore the interface of Linux together. Ask the class to compare and contrast the Linux interface with their computer's own operating system. 

- They may notice that there is not much difference between the two. Mention that a lot of Linux may seem similar to Unix systems likes Windows or Mac OS. Remind students that a key feature of Linux, compared to Unix, is the _free, open-sourced_ conponent. 

- Assure students that while different distributions provide different functions, we will be covering the shared basics among _all_ major Linux distributions. 

- Also, remind students that the virtual machine works as a sandbox. What we make and do in the VM will not affect the students' host computer. 

Now we will move on to our completing our first Linux task: executing basic commands.

-----

### 6. Direct Instruction: Command Line Demo (0:05)

Tell students that the first tasks they will complete in Linux will be achieved by working on the command line. 

In a moment, they will work on their command line skills with an activity. Before they get started, perform a quick review of some basic functions:

- Open a terminal and present the following  functions:  `mkdir`, `cd`, `ls`, `cp`, `touch [file]`.
- One by one, as students identify each function, execute a simple task using each command. 
- Answer any student questions before starting the next exercise. 

Answer any questions before moving onto the next student activity. 

### 7. Guided Practice: Command Line Refresher (0:15) (Clock = 1:20)

In this activity, students will refresh their knowledge of command line functions. They will use the basic functions: `mkdir`, `cd`, `ls`, `cp`, `touch [file]`.

- Send students the following file. 

- [File](Instructions2.md)

- Instructions: 

    - In this activity, you will refresh your knowledge of command line functions. 

    - Remember that by using your command line, you can navigate your computer, create and read files, and create new directories. 

    - Try to work without referencing any cheat sheets. See what you remeber from the last unit. Only if you are get stuck, then consult any references or cheat sheets.

    - Okay, it's **hypothetical situtation time**! _You're packing up and moving out of your childhood home. "Congratulations, it's about time", say your parents.  But before you move out, you have to pack up all your stuff._ 
    
    - In this exercise, we are going to simulate the process of packing up and moving out via files and directories on the command line:

        1. To begin, create a directory titled: `The Old House`.
        2. In `the old house`, you have _all this stuff_. Document the contents of your house that you want to take to your new apartment. Creating the following files: 
            - `My clothes` 
            - `My books` 
            - `My video games` 
            - `My toothbrush` 
            - `My life-size cardboard cut out of NY Giant's Quarterback Eli Manning`
            - `My photo album`
        3. Let's get a little more organized. Within your current working directory, make another directory called `My stuff`. Then move all your files into `My stuff`.
        4. You really want to pack up your photo album, but your parents also want to keep those photos and hang them all over the walls on `the old house`. Make a copy of `My photo album`. Move the copied file out of `My stuff` and into `The Old House`. 
        5. Time to pack up. Move '`My stuff` from `The old house` and into a new directory: `My suitcase`.
        6. Everything won't fit. On second thought, you haven't played your video games in over 2 years, so there's no need to pack it up. Delete the file `my video games`. 
        7. Move `my suitcase`  into a new directory outside of `The old house`. Call it  `my new apartment`. 
        8. You made it to your apartment. Make sure all your stuff made it too. List the contents of `my suitcase`. 
        9. Move the files out of `my backpack` and into `my new apartment`. 
        10. The  apartment is a little cramped. Everything won't fit. Move `my life-size cardboard cut out of NY Giant's Quarterback Eli Manning` from `my new apartment` to a new directory called `my self storage unit`. 
        11. You're all done moving. The place looks great. Good job.
    
    - Once you are finished, compare with a fellow student. 
    - How many lines did each of you take to complete your tasks? Could you have used any other commands or short cuts to mitigate the steps taken? 

Wal around the room and monitor the class's progression throughout the exercise. 

### 8. Direct Instruction: Review Command Line (0:10) **(Clock = 1:30)**

Once the students have finished working, call attentio back to the class. 

- Remind students that working on the command line is a lot like learning a foreign language or any new skill: continued practice is essential to gaining competency. 

- If students are feeling confident in their terminal skills, let them know that they we will be expanding their repertiore of terminal commands in the coming lessons. If students are not feeling confident, ensure them that they will have plenty more opportunities to practice on the command line. 

Spend the remaining time of this review to emphasis the importance of the command line. While GUIs might be more accessible on your computer, in the world of cybersecurity, students will not have the luxury of working in GUI. If applicable, explain why and how you used the command line in any previous jobs. 

### 9. Direct Instruction: Permission (0:15) 

### 10. Guided Practice: Inspecting Permissions and Symbolic & Octal Notation (0:20) (Clock = 2:05)

### 11. Direct Instruction: Review Inspecting Permission (0:10)

#### BREAK (0:15) (Time = 2:30)

### 15. Direct Instruction: chmod, su, sudo, chown Demo (0:10)

### 16. Guided Practice: Setting Permissions (0:20) (Clock = 3:00)

### 17. Direct Instruction: Wrap up and Review Setting Permissions (0:05)

-------

### Copyright

Trilogy Education Services © 2018. All Rights Reserved.

