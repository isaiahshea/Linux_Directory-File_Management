<h1>Linux Directory and File Management</h1>



<h2>Description</h2>
<b>
In a recent lab activity, I demonstrated my adeptness in Linux systems and command-line navigation, acquiring essential skills for a security I role. Effectively communicating with the operating system through the shell, I mastered core commands, enabling me to navigate the Linux file structure and extract valuable information from files. This proficiency proved invaluable during tasks such as investigating unauthorized access, where I successfully navigated to and analyzed a user access report.

<br/>Throughout the lab, I showcased my ability to remotely manage and analyze files via a Linux shell, a critical skill for a security I operating without a graphical user interface. I strategically located specific files, thoroughly examined their contents, and answered multiple-choice questions based on the insights derived from these files. This experience underscores my competence as a security I, highlighting my capacity to navigate, manage, and analyze files remotely in a Linux environment—a skill set crucial for any cybersecurity professional.
</b>
<br />
<br />
<br />
<br />



<h2>Identity and Access Management in Linux: Analyzing File Permissions and Ensuring Security Compliance in the Projects Directory</h2> 

- <b>File and Directory Examination:</b> Analyzing files and directories for information and security assessment

  - <b>Description:</b> In this sequence of actions, I systematically explored directories, listed files, and examined their contents in a bash environment. This process involved navigating through the directory structure, ensuring accurate commands for listing files, and correcting any errors encountered along the way. The objective was to gain insights into the directory and file structure, demonstrating proficiency in file system navigation and analysis.
    - Listing Directories: I check available directories in the home directory: "logs," "projects," "reports," and "temp."

    - Navigating to Reports: Moved to the "reports" directory.

    - Listing Files in Users Directory: Listed files in the "users" directory.

    - Navigating to Users Directory: Changed the directory to "users."

    - Listing Files in Users Directory: Listed the files in the "users" directory.

    - Viewing Contents of Q1 File: Examined the first few lines of the "Q1" file.

    - Navigating Back to Home Directory: Returned to the home directory.

    - Navigating to Logs Directory: Entered the "logs" directory.

    - Viewing Contents of Server Logs File: Used cat command to view the contents of the "server logs.txt" file.

<p align="center">
<img src="https://imgur.com/OyuW4hL.png" height="85%" width="85%" alt="Directory discovery and File exploration"/>
</p>

<h2>Securing File Permissions in the Directory: Access Management</h2>

- <b>File and Directory Examination:</b> Analyzing files and directories for information and security assessment

  - <b>Description:</b> I meticulously examined and managed file permissions within the /home/researcher2 directory. Navigating through the projects directory, I analyzed permissions, identified the group owner as "research_team," and checked for hidden files. The focus then shifted to securing file permissions, specifically restricting other users from writing. Through targeted adjustments using the chmod command, I reinforced access control and enhanced overall system security. This hands-on exploration underscores the significance of precise permission management for a robust and secure system configuration.

    <b>Task 1: Check File and Directory Details</b>
    - Navigated to the "projects" directory: Changed the current working directory.

    - Listed the contents and permissions of the "projects" directory: Examined detailed file listings, including permissions.

    - Identified the group that owns the files in the projects directory: The group owner is "research_team."

    - Checked for hidden files in the projects directory: Confirmed the absence of hidden files.
    
    <b>Task 2: Check and Manage File Permissions</b>
    - Checked for write permissions for other users in the projects directory.
      - Examined permissions to identify files allowing write permissions for other users.
      
      - Identified "project_k.txt" as granting other users write permissions.

    - Changed permissions of "project_k.txt" to remove write permissions for other users.
      - Modified file permissions to disallow write access for other users.
    
    - Checked permissions of "project_m.txt."
      - Examined permissions to ensure it is restricted.
      
      - Confirmed that the group and other users do not have read or write permissions.





<p align="center">
<img src="https://imgur.com/uN1c9eA.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
