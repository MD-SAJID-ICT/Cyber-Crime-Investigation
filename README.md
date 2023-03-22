<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">Cyber Crime Investigation</h1>
  <br>
  
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/images/banner%20cyber%20crime.jpeg">

  

<h3 align="center">Project Module - Digital Forensics</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#1-overview-of-the-case">OVERVIEW OF THE CASE</a>
      <ul>
        <li><a href="#11-required-findings">Required Findings</a></li>
        <li><a href="#12-acceptable-internet-use-policy-for-ubb">Acceptable Internet use policy for UBB</a></li>
        <li><a href="#13-unacceptable-behaviour">Unacceptable behaviour</a></li>
      </ul>
    </li>
     <li>
      <a href="#2-literature-review">Literature review</a>
      <ul>
        <li><a href="#21-critical-discussion">Critical Discussion</a></li>
        <li><a href="#22-references">References</a></li>
      </ul>
    </li>
     <li>
      <a href="#3-evidence-file">Evidence File</a>
      <ul>
        <li><a href="#31-details-of-the-evidence-file">Details of the Evidence File</a></li>
        <li><a href="#32-hash-value-of-the-evidence-file">Hash value of the Evidence File</a></li>
      </ul>
    </li>
     <li>
      <a href="#4-analysis-process--artefacts">Analysis Process & Artefacts</a>
      <ul>
        <li><a href="#41-suspected-user">Suspected user</a></li>
        <li><a href="#42-suspicious-activity">Suspicious Activity</a></li>
        <li><a href="#43-log-files-analysis">Log files Analysis</a></li>
        <li><a href="#44-suspicious-web-history">Suspicious web history</a></li>
      </ul>
    </li>
    <li><a href="#5-the-toolkit">The Toolkit</a></li>
    <li>
    <a href="#6-probable-mitigation">Probable Mitigation</a>
    </li>
    <li>
    <a href="#contact">Contact</a>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
# About The Project




<p align="right">(<a href="#top">back to top</a>)</p>




<!-- 1. Imaging Exercise -->
# Task 1: Imaging Exercise 

## 1.1 Requirements of Imaging Exercise

### 1.1.1 Part (A)  

Using the ‘ImageFile**.001’ image file that you have been assigned, produce a brief report showing that you can perform the following tasks: <br>
•	Demonstrate that you are working on a correct image file (i.e. show you can get the same hash as that provided to you). <br>
•	Create a single EWF/E01 image file, using (max) compression. Demonstrate that it has been correctly and accurately created. <br>
•	Create an EWF/E01 image that has been split up into at least 5 parts (there is no need for these to be equally sized). This does not need to be compressed. Demonstrate that it has been correctly and accurately created, and provide a list of the hashes for all the split parts of the image. <br>
It is essential that all of these stages are documented with screenshots and a brief explanation. You are not handing in the image files, you are producing a short report with screenshots to prove that you have done these operations. Make your screenshots large, clear and legible or you will be marked down substantially. <br>

### 1.1.2 Part (B) 

Using an image file you created in Part A (i.e. not the .001 file), demonstrate using two different methods/pieces of Forensic software that the image is verifiably correct. Using two forensic tools to achieve the same result is a standard Digital Forensics technique called Dual Tool Verification.  

### 1.1.3 Part (B)

Draw a sketch/diagram that would be suitable for members of a jury who are not technically knowledgeable, on what a “Write blocker” is. Within your answer you must explain the purpose, function and available options for Write Blocking. 

## 1.2 Report of Imaging Exercise

### 1.2.1 Part (A)

The image file which was provided to me was named “ImageFile8.001”. In the image file, I analyzed it with Autopsy tools and got some hash values. And this hash value is perfectly similar to the provided image file.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/1.png">
</p>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/4.png">
</p>

So it would be proven that I am working on a correct image file.<br>

I created an image file named “Sports.E01” by FTK Imager. Which has a total of 12 parts.
The details of FTK imager tools-

  ```sh
  Created By AccessData® FTK® Imager 4.5.0.3
Case Information:
Acquired using: ADI4.5.0.3
Case Number: 120
Evidence Number: 5
Unique description: Sports Car Stealing
Examiner: Forensics Institute
Notes: Digital Forensics Investigation
--------------------------------------------------------------
Information for E:\Encase_2\Sports:
Physical Evidentiary Item (Source) Information:
[Device Info]
Source Type: Physical
[Drive Geometry]
Cylinders: 6,527
Tracks per Cylinder: 255
Sectors per Track: 63
Bytes per Sector: 512
Sector Count: 104,857,600
[Physical Drive Information]
Drive Model: VBOX HARDDISK
Drive Serial Number: VB58036779-832520e8
Drive Interface Type: IDE
Removable drive: False
Source data size: 51200 MB
Sector count: 104857600
[Computed Hashes]
MD5 checksum: 784dc9b7b4f5eef4e123480c0324dc68
SHA1 checksum: f4e9dd70116dffd6c9bfc7ac92d76561152ae796
  ```
  
 <b>Image Information:</b/
 
   ```sh
  Acquisition started: Sat Nov 19 20:20:36 2022
Acquisition finished: Sat Nov 19 21:01:18 2022
Segment list:
 E:\Encase_2\Sports.E01
 E:\Encase_2\Sports.E02
 E:\Encase_2\Sports.E03
 E:\Encase_2\Sports.E04
 E:\Encase_2\Sports.E05
 E:\Encase_2\Sports.E06
 E:\Encase_2\Sports.E07
 E:\Encase_2\Sports.E08
 E:\Encase_2\Sports.E09
 E:\Encase_2\Sports.E10
 E:\Encase_2\Sports.E11
 E:\Encase_2\Sports.E12
  ```
<b>Image Verification Results:<b>

  ```sh
  Verification started: Sat Nov 19 21:01:19 2022
Verification finished: Sat Nov 19 21:20:32 2022
MD5 checksum: 784dc9b7b4f5eef4e123480c0324dc68 : verified
SHA1 checksum: f4e9dd70116dffd6c9bfc7ac92d76561152ae796 : verified

  ```

### 1.2.2 Part (B)

I analyze the Sports.E01 image file from both of autopsy and FTK Imager tools.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/5.png">
</p>

  ```sh
  Created By AccessData® FTK® Imager 4.5.0.3
Case Information:
Acquired using: ADI4.5.0.3
Case Number: 120
Evidence Number: 5
Unique description: Sports Car Stealing
Examiner: Forensics Institute
Notes: Digital Forensics Investigation
--------------------------------------------------------------
Information for E:\Encase_2\Sports:
Physical Evidentiary Item (Source) Information:
[Device Info]
Source Type: Physical
[Drive Geometry]
Cylinders: 6,527
Tracks per Cylinder: 255
Sectors per Track: 63
Bytes per Sector: 512
Sector Count: 104,857,600
[Physical Drive Information]
Drive Model: VBOX HARDDISK
Drive Serial Number: VB58036779-832520e8
Drive Interface Type: IDE
Removable drive: False
Source data size: 51200 MB
Sector count: 104857600
[Computed Hashes]
MD5 checksum: 784dc9b7b4f5eef4e123480c0324dc68
SHA1 checksum: f4e9dd70116dffd6c9bfc7ac92d76561152ae796
  ```
Here we can see that both tools' hash values are the same. So we can say that the image file is 
dual tool verified.

### 1.2.3 Part (C)

<b>Write Blockers:</b><br>
A tool called Write Blocker is intended to stop any write access to the hard drive, allowing read-only access to the data storage devices without jeopardizing the data's integrity. If utilized properly, a write blocking can ensure that the chain of custody is protected. A set of general principles for write-blocking restrictions have been published by NIST:<br>
● The write-blocker tool must prevent any changes to a protected drive.<br>
● No activities on a disk that is not protected may be stopped by the write-blocker utility.<br>
● The write-blocker program must not obstruct access to or collection of data from any drive.<br>
Hardware and software write blockers are the two main categories of write blockers. The same goal of both varieties of write blockers is to stop any writes to storage devices.<br>
The block diagram of write blockers:<br>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/5.png">
</p>

● A hardware write blocker (HWB) is a hardware device that attaches to a computer system with the primary purpose of intercepting and preventing (or ‘blocking’) any modifying command operation from ever reaching the storage device. Physically, the device is connected between the computer and a storage device. The gadget is 
physically connected to a storage device and a computer.<br>
● By observing and filtering drive I/O commands transmitted by an application or OS over a specific access interface, a software write block tool performs its function.


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- 2. Search and Seizure -->
# Task 2: Search and Seizure 

### 2.1.1 The Scene

The scene should include at least 1 significant large device (laptop or larger) and a small collection of media or smaller significant artefacts (such as phones, USB sticks, CD/DVD etc.). The scene should also contain non-digital artefacts that may be relevant such as paperwork, post-it notes etc.<br>
There is no need to specially stage the setting if you already have a suitable workspace or desk area to demonstrate searches on.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/2.png">
</p>
<h3 align="center">Figure 1 – A Complex Digital Forensics Search Environment</h3>

If figure 1 is your room, then we are not expecting you to process all of it. Describe your plan for the whole scene, then declare the desk for example on the left-hand side as your zone, and process everything on and around that.

### 2.1.2 Requirements of Search and Seizure

You must produce a report documenting the search. Within the report you must contain information on:<br>
A)	A diagram of the scene. Add to the diagram Safety issues, Anticipated Assistance you would require for this kind of setting and the kind of Interview, and Information Gathering you would need to conduct. Please keep your plan related to your specific scenario, and do not put irrelevant general information (e.g. a SWAT team just incase there is a gun on the premises. Just no).<br>
B)	Provide a set of legible photographs to show an overview of the scene, including a photograph of the zone(s) you have searched. Individual photographs of all the notable objects in the scene, highlighting exhibit reference numbers. You do not need to photograph all 6 sides of the objects, but it is necessary to capture the object in situ, and advantageous to capture serial numbers and/or identifying marks etc. <br>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/3.png">
</p>
<h3 align="center">Figure 2 - An example of an in situ photograph showing the exhibit reference number of an item about to be produced</h3>

C)	Produce an Exhibits Record table for your ‘seized’ items (i.e. the items you would be taking away in a real search). Each item must have the following information recorded for it (even if some information is duplicated):<br>
•	Record location (zone) where all the exhibits come from<br>
•	Who seized the item.<br>
•	What time the item was taken<br>
•	The seal number of the bag (or if improvising a signature seal you need a record of the signature)<br>
Remember that each individual item needs its own record with the above information, because in the real world multiple people would be seizing different items.<br>

D)	You are to bag and photograph an item from your crime scene using an improvised seal. A clear evidence reference number is needed to be visible, a signature seal must be visible and a clear sealing of the bag must be shown (this may require a couple of close-in pictures as cello tape is particularly hard to see). You do not need to photograph the intermediate stages of constructing the improvised seal, a final sealed exhibit is sufficient. <br>


## 2.2 Reports of Search and Seizure

### 2.2.1 The Search

In Figure 1 we can see that, a lot of objects. By searching every detail in this place, we can find that-<br>
• 3 CPU<br>
• 1 Hard-disk on right-below<br>
• A lot of Ethernet cables<br>
• A monitor<br>
• Power Supply<br>
• Keyboard and mouse<br>

For the details investigation, here I need the Hard-disk by which I can investigate of defendant’s-<br>
• Backup files<br>
• Browsing History<br>
• Downloads<br>
• Pictures<br>
• Videos <br>
• Social media Communication<br>
• Passwords and Hidden files.<br>
• Metadata (EXIF, XMP, IPTC)<br>
In this case, for the investigation purpose generally use an autopsy tool<br>

### 2.2.2 Individual Photographs of Evidence

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/7.png">
</p>
<h3 align="center">Evidence No: 1</h3>
<h3 align="center">Figure B: A situ photographs showing the exhibit reference number of Hard disk
</h3>

### 2.2.3 Exhibits Record table for your ‘seized’ items

| Seized   |                Details                   |
| ----------| -------------------------------------- |
| CPU | ● Record Location: On encase spot<br>● Seized by Chief Investigation Officer<br>● Time: 19-11-2022<br>● Seal Number: 2<br> |
| Hard Disk | ● Record Location: On encase spot<br>● Seized by Chief Investigation Officer<br>● Time: 19-11-2022<br>● Seal Number: 1<br |

For the purpose of investigation, the sealed exhibit is sufficient. Here I seized The CPU and the Hard Disk.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- 3. Written Evidence and Opinion -->
# 3. Task 3: Case Study

## 3.1 Case Background


### 3.1.1 Defendant

John CHURCHILL (d.o.b. 1/1/2002)<br>
A Computer Science (Artificial Intelligence) B.Sc. Student at STFU. Room 216, Halls of Residence.

### 3.1.2 Circumstances of the Case:

Approximately at midnight on the  19th of November 2022, two students (Harry TURNBULL and Jade GREY) who were visiting the Halls of Residence for the South Thames Fictional University walking into room 216 by mistake.
Both TURNBULL and GREY had drunk a significant quantity of alcohol.
Both TURNBULL and GREY observed the defendant CHURCHILL sat at his desk. GREY approached CHURCHILL and realizing that they were in the wrong room tried to apologise and make light of situation. When she tried to look at his screen saying that he “shouldn’t be looking at porn all night”, CHURCHILL became aggressive. She states that she realized she was looking at a large-scale indecent photograph of a child on the screen, not adult pornography.
CHURCHILL’s aggressive behaviour towards GREY caused TURNBULL to intervene, which lead to loud shouting and a scuffle breaking out between CHURCHILL and TURNBULL. University security arrived quickly and removed TURNBULL and GREY from room 216. Officers from the Met Police were called to attend the scene as TURNBULL and GREY were belligerent towards the security.
When uniformed officers arrived, GREY stated that the defendant was watching Child Porn on his laptop computer, although TURNBULL states he did not see the computer. When officers attended room 216 to question the defendant, they noticed that on the screen was a web page relating to wiping software. As such the laptop computer was seized and at that time the defendant was arrested. A mobile phone has also been seized and sent for separate examination. Nothing of note is currently reported for the phone.

### 3.1.3 Police Action Taken

The computer was processed by the Greenwich Hi-Tech Forensics Unit and an automated search for indecent photographs was positive. These are present within the web cache area of the disk. Internet history extraction shows indecent terminology being searched for.
The defendant has stated that he was researching ‘Deep Fake’ technology as part of his studies. 
He admits that he wanted to make humorous meme-type pictures using classmates or lecturers at university, but whilst researching deepfakes he found articles about morphing porn actors and regular people.  
He acknowledges that whilst trying to find pictures he could use to make deep fake pictures or “composites”, he may have strayed into pornographic sites that included indecent photographs, and this may have caused these pictures to be downloaded onto his computer’s ‘web cache’.
Defendant states that he did not search for indecent terminology.
Defendant states that there was no attempt to make ‘revenge porn’, and he just wanted to find out how pornographic deep fake pictures could be made as he had “read about it on the BBC”.    

## 3.2 Tasks

Conduct an individual analysis on the provided image file. Below are a set of 3 questions and a request for an opinion sought from the ‘Crown Prosecution Service’. Produce an MG11-style statement detailing the results of your analysis, dealing with the answers to the questions and your opinion. Use the lecture material as guidance on how to structure the statement but it must conform to the normal statement style (be in first person, not contain pictures etc.) your paragraphs must be numbered, it must include details on who you are, your duties as an expert, and technical details of the system being examined. 

### 3.2.1 Question 1

The defendant has stated that he uses the laptop to play games online and do some university work, mostly doing his social activities on his phone. Are there artefacts present on the exhibit that support or undermine this assertion.

### 3.2.2 Question 2

Is there any evidence to show that the indecent photographs have been saved or accessed?

### 3.2.3 Question 3

If the laptop has been bought second-hand, is it possible that any discovered artefacts can be attributed to previous owners?

### 3.2.4 Opinion

Can you support the defendant’s statements about seeking to make composite pornographic pictures? We are particularly interested if there is anything on the device which indicates that the defendant, or anyone else, has made conscious effort to search or access indecent material.<br> 
Currently there is no allegation that someone else used the computer. This computer is allegedly second-hand, and a recently bought refurbished computer.His old computer was recently reported stolen (there is a reported Crime Reference Number to confirm this).

## 3.3 Scenario Rules

Pictures of the Actor Willem Dafoe shall be considered the victim Giles Trent.<br>
Standard rules: Pictures of cats should be considered Indecent Photographs of Children, or any terminology relating to cats should be considered notable terminology relating to Indecency. Pictures or terminology of dogs should be considered legal sexual content.


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- 4. Analysis Process & Artefacts -->

# 4. Analysis Process & Artefacts

## 4.1 Summary Of Findings

### 4.1.1 With respect to question 1

I found a shadow gaming web search on the web cache.
<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/8.png">
</p>
 
Here, I also found the research work on the topics Deepfake of a BBC journal.
<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/9.png">
</p>
<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/10.png">
</p>

There also have some social activity and the platform was Outlook. Where defendant CHURCHILL Send a mail prof Trent. But here the content of the mail was fishy.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/11.png">
</p>
 
### 4.1.2 With respect to question 2

I found a lot of indecent photographs that have been saved or accessed. I found a lot of child pornography pictures that are saved on the defendant’s laptop. Some of them I show here.

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/12.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/13.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/14.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/15.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/16.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/17.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/18.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/19.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/20.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/21.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/22.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/23.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/24.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/25.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/26.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/28.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/29.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/30.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/31.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/32.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/33.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/34.png">
</p>

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/35.png">
</p>

Here I mention the folder location where I find the photography of children’s pornography.

```sh
  Path: 
/img_Operation Canary 
Wharf.E01/vol_vol2/Users/IEUser/AppData/Local/Microsoft/Windows/Temporary Internet 
Files/Content.IE5/3LEMN813/ 
And the metadata of this folder isName /img_Operation Canary 
Wharf.E01/vol_vol2/Users/IEUser/AppData/Local/Microsoft/Windows/Temporary 
Internet Files/Content.IE5/3LEMN813 
Type File System 
MIME 
Type null 
Size 208 
File Name
Allocation Allocated 
Metadata 
Allocation Allocated 
Modified 2022-11-19 06:17:04 BDT
Accessed 2022-11-19 06:17:04 BDT
Created 2022-11-18 02:05:55 BDT
Changed 2022-11-19 06:17:04 BDT
MD5 Not calculated 
SHA-256 Not calculated 
Hash 
Lookup 
Results 
UNKNOWN 
Internal ID 2091 
  ```
### 4.1.3 Web cache

In the web cache there I also found some web searches. Which directly indicates the child’s pornography.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/36.png">
</p>

File Metadata of web search:

```sh
  Name /img_Operation Canary 
Wharf.E01/vol_vol2/Users/IEUser/AppData/Local/Microsoft/Windows/WebCache/WebC
acheV01.dat 
Type File System 
MIME 
Type application/octet-stream 
Size 27328512 
File 
Name 
Allocati
on 
Allocated 
Metadat
a 
Allocati
on 
Allocated 
Modifie
d 2022-11-19 06:22:33 BDT
Accesse
d 2018-03-07 14:06:24 BDT
Created 2018-03-07 14:06:24 BDT 
Changed 2022-11-19 06:22:33 BDT
MD5 0cdf08693f556f7420985834ce81b1b0 
SHA256 3ce916df67b93fec57ff4fbec7260cb41491b8b30610a373c3074566ec5a2190 
Hash 
Lookup 
Results 
UNKNOWN 
Internal 
ID 12703
  ```


### 4.1.4 With respect to question 3

I found a file named overview.rtf. Their defendant mentioned that “This new laptop is a piece of crap.”

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/37.png">
</p>
And the metadata of this file is-

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/38.png">
</p>
We can see here the file creation date was 2022-11-09. But the attempts defendant occurs after this time.<br>

I also found a web search from the web cache where the defendant also searches for a new laptop.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/38.png">
</p>




### 4.1.4 Other Findings

In addition to the above I also found, Some unethical activity of the defendant.<br>
 On the defendant’s CHURCHILL statement, he state that wanted to make humorous meme-type pictures using classmates or lecturers at the university. But on the image file, I found many deepfake porn pictures of Professor Giles Trent.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/39.png">
</p>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/40.png">
</p>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/41.png">
</p>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/42.png">
</p>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/45.png">
</p>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/46.png">
</p>

 The defendant also makes deepfake porn of his classmate Rosie. Which I found in the Project Rosie folder. And there I also found other’s Deepfake porn. Maybe it will be Mrs. Giles Trent.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/47.png">
</p>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/48.png">
</p>


<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/49.png">
</p>


<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/50.png">
</p>

● I also found a file named ‘overview.rft’ which has some self-conversation bad comments from the defendant and where the defendant mentioned that he ruined Giles Trent’s life.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/52.png">
</p>

● From the web cache, I also found some web search which is also fishy.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/53.png">
</p>

● There, I also found that the defendant sends a mail to Professor Giles Trent. Here we see that defendant tries to blackmail Professor.

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation/blob/main/Screenshots/54.png">
</p>

## 4.2 Detailed Findings for Exhibit ABC/1
  
Additionally, in there locate the <b>"autoexec.bat"</b> file in the VM's <b>/home/Documents</b> directory.

  
● The file ‘Operation Blue Canary Wharf’ is the forensic image of the exhibit, which is a laptop computer.<br>
● The currently installed operating system is Windows 7 Enterprise with a recorded installation/update date of 2018/03/07. There is a single Default user account present named IEUser which has no password set for it. My examination shows that the last recorded use of the computer was on Nov 19, 2022.
<br>
● Question 1: The defendant has stated that he uses the laptop to play games online and do some university work, mostly doing his social activities on his phone. Are there artefacts present on the exhibit that support or undermine this assertion.<br>

Answer: It is true that the defendant uses the laptop to play games and do some university work. Because In the web cashed I found some web searches about shadow gaming. I also found some research work about deepfake in BBC journals.<br>

● Question 2: Is there any evidence to show that the indecent photographs have been saved or accessed?<br>

Answer: There have a lot of photographs of child pornography on the defendant’s laptop. And he saved these photographs in the folder of-

```sh
  /img_Operation Canary Wharf.E01/vol_vol2/Users/IEUser/AppData/Local/Microsoft/Windows/Temporary Internet Files/Content.IE5/3LEMN813/
  ```
● Question 3: If the laptop has been bought second-hand, is it possible that any discovered artifacts can be attributed to previous owners?<br>

Answer: It is true that the laptop has been second-hand. Because the defendant searches for an old laptop on the web. And in the ‘overview.rtf’, there he mentions that “This new laptop is a piece of shit”. But After analyzing the metadata of all findings, I assure that the discovered artifacts cannot be attributed to previous owners. Because all discovered artifactsacts are accessed or saved after the creation date of the ‘overview.rtf’ file. In this case, the creation and modification date of ‘overview.rft’ was 09-11-2022. The folder where I discovered the image files and where the photography of child pornography, creation, and modification date was 19-11-2022.<br>

● Other Findings: The defendant is directly responsible for making the Deepfake porn photo. Where the victim was-
==>Professor Giles Trent
==>And his classmate Rosie

## 4.3 Opinion

According to the all evidence, defendant CHURCHILL saved and access the photographs of children’s pornography. And he is also responsible for Deepfake porn where the victim was Professor Giles Trent And his classmate Rosie.

## Disclosure
● I confirm that I have complied with my duties to record, retain and reveal material in accordance with the Criminal Procedure and Investigations Act 1996, as amended.

● In  the event my opinion changes on any material issue, I will inform the investigating officer as soon as reasonably practicable and give reasons.

## 4.4 Duty to the Court

I declare that I understand that my duty, including providing written reports and giving evidence, is to assist the court and that this duty overrides any obligation to the party who has engaged me. I can confirm that I believe that I have complied with my duty.


  
  <p align="right">(<a href="#top">back to top</a>)</p>
 
 <!-- 5. The Toolkit -->
 # 5. The Toolkit 
 


| toolkit   |                Notes                   |
| ----------| -------------------------------------- |
| Autopsy | Autopsy is a powerful and flexible digital forensics platform that provides a range of tools for investigating digital evidence. It is widely used in law enforcement, government, and corporate investigations, and its open-source nature makes it accessible to a wide range of users. Some of the key tools available in Autopsy include:<br>● Forensic Imaging<br>● Data Carving<br>● Keyword Search<br>● Timeline Analysis<br>● Hash Filtering<br>● Metadata Extraction<br>● Reporting |
| Nano  | Nano is a text editor that is widely used on Unix-based operating systems. Some of the key tools available in Nano include:<br>● Basic Text Editing<br>● Syntax Highlighting<br>● File Management<br>● Search and Replace<br>● Multi-buffer Editing<br>● Keyboard Shortcuts |
| Grep | Nano is a text editor that is widely used on Unix-based operating systems. Some of the key tools available in Nano include:<br>● Basic Text Editing<br>● Syntax Highlighting<br>● File Management<br>● Search and Replace<br>● Multi-buffer Editing<br>● Keyboard Shortcuts |
| Kali Linux | Kali Linux is a popular Linux distribution that is widely used for penetration testing and digital forensics. Some of the key features of Kali Linux include:<br>● Security Tools<br>● Live Booting<br>● Customizability<br>● Community Support<br>● Documentation<br>● Virtualization Support |

<p align="center"> 
Table of Toolkits
  </p>
  
  <p align="right">(<a href="#top">back to top</a>)</p>
  
 

<!-- CONTRIBUTING -->
# Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
# License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
# Contact

  <b>Md Zahid Hossain Sajid</b> - [@My_Linkedin](https://www.linkedin.com/in/md-zahid-hossain-sajid-85bbab185/) - zahidhossainsajid@gmail.com

Project Link: [https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation.git](https://github.com/MD-SAJID-ICT/Cyber-Crime-Investigation.git)

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/tareqraihan926
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
