<!--########################################### -->
<!--### hAckDHD -->
<!--## methodology of hacking and defending -->
<!--# -->
<!--## this will let me lay out my methods in a markup form -->
<!--# -->
<!--##################################################### -->


# BUILDING A ~~FUCKING~~ METHODOLGY #

## RESOURCES THAT HELPED

- https://buymeacoffee.com/d3adshot/extras
- https://corelight.com/resources/glossary/false-positives-cybersecurity
- 

# RED TEAM

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

# BLUE TEAM

## THE BASICS

### 5 W’S

- WHO
    - WHO TRIED TO GET IN
- WHAT
    - WHAT CAUSED THE ALERT
- WHEN
    - WHEN DID THIS ALERT COME IN
- WHERE
    - WHERE ARE THE MACHINES BEING ACCESSED
- WHY
    - WHY IS THIS CAUSING AN ALERT

### WHAT SHOULD I KNOW TO BE AN AWESOME BLUE TEAMER

### SOC ANALYST

### DEV SEC OPS

### DETECTION ENGINEERING

### THREAT HUNTING

## HOW TO TAKE NOTES IN A TICKET

- Taking notes in a ticket are important. Just saying “FP” or “Known Activity” just does not cut it.
- “So how do i take effective notes”
    - To take effective notes keep in mind this phrase
        - “If it is not in the ticket it didn't happen”

### WHAT TO PUT IN THE TICKET

- DETAILS
- EVIDENCE
- SHORT SUMMARTY TLDR

Why for the list above?

Think of it this way, You need to be able to articulate your ticket so the following people can understand the ticket, why its important, and what the impact/action steps required are

- Your team
    - Another analyst should be able to see the details and understand where you conclusion was drawn
- The CISO/CTO of the organization
    - The CISO and CTO are busy. they have employed a team of skilled workers under them and need the quick and simple version
        - whats the impact
        - whos impacted
        - what is needed
- Your HR/Legal department
    - Imagine having to explain this to your team member in accounting that doesnt understand what it means to verify if the computer tower has power.
- Example
    
    ```jsx
    Entry (Time stamp)
    --details
    IP:192.168.1.0
    time: 1201 02022026
    Parent_Process: cmd.exe
    Child_process: reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve
    Location: Russia
    User: aDmIn
    Device_Hostname: Windows_Rules.domain
    
    --evidence
    Find event logs and put the ID here with short shippits 
    
    EVENT 1234 (hyperlink if the platform allows or place below the id)
    ==============================
    data shown below shows the user opening the command prompt
    (enter relevent data copy paste)
    
    Event1233
    =====================
    User login from russia
    (enter data)
    A
    IP 192.168.1.0
    ========================
    Ip is found to be malicious per Virustotal and AbuseIPDB
    (vt link)
    (AbuseIPDB link)
    
    --tldr
    ==================================
    The user "aDmIn" logged in the computer at (time) and executed 
    the code for a reg edit. Surrounding the time stamps there are no malicious actions obsrerved
    The command at hand allows for a left click menu for win 11 to not add the "add more to the menu
    No malicious activity is found however the IP is from russia and is not in our geolocation allow list
    Block reqeust created for the ip and users account has been locked for investigation. Virus scan running for the users pc
    ```
    

## WHAT IS CONSIDERED A FALSE POSITIVE/FALSE NEGATIVE

WOAH WOAH WOAH. WTF is a False Negative????? False Positive sounds self explanatory 

- False Positive
    - A false positive in cybersecurity is an event or alert that is incorrectly identified as malicious or a threat when it is benign - Corelight
    - What the SOC Analyst says it is
        - An alert that is just noise and needs tuned.
            - While the phrasing above can be true we must know that the alert is truly a false positive. Some environments will have alerts that show “known” behavior but cant be tuned out due to the nature of the commands being ran have been known to be used maliciously. It does not hurt to take a moment and recheck the alerts to ensure that they are sill being executed in the manner you expected while tuning efforts are being made to dial in the ticketing system.
- False Negative
    - These are any blue teamer worse nightmare. The alert that ether is masked as not malicious or is undetected
    - A false negative occurs when a security tool fails to detect a genuine threat, allowing a malicious actor to operate undetected on the network. - Corelight

## WHAT IS THIS ALERT SAYING????

The biggest assistance you can gain during alert triage is GOOGLE!!!!!

Learn what the alert is firing on and what it is used for

LUSRMGR.MSC - If you don't know what this is just throw it in GOOGLE. 

There will not always be a runbook/playbook that will explain the step by step of how to push buttons to do your job 

Many of the products you use will have extensive documentation and forums that can help you find out why alerts are firing off.  Don't take the forums to heart as there are many internet warriors out there who do not know what an [RFC 1918](https://www.rfc-editor.org/rfc/rfc1918.html) is and still throws them into tools to see if they are malicious.

## PLACE HOLDER

- LIST
    - LIST

# MY METHODOLOGY

# RED TEAM

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

# BLUE TEAM

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

# WEB APPLICATION TEST

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

# EMAIL

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

# RED TEAM

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST

## NETWORK

- LIST
    - LIST