Download Link: https://assignmentchef.com/product/solved-lab-activity-1-basic-for-unix-linux
<br>
<table>

 <tbody>

  <tr>

   <td width="585"><strong>Lab Activity 1: Basic for Unix/Linux</strong></td>

  </tr>

 </tbody>

</table>




<strong>Objectives</strong>




<ul>

 <li>Develop the skills to find, read, and understand sources of information about commands usage.</li>

 <li>Identifying appropriate commands needed to perform given tasks</li>

</ul>




<strong>Submissions (2pts)</strong>

Once you’ve completed all the activities, perform the following steps for submission:

<ol>

 <li>Move the files lab1.1, 2, and lab1.3 into IFT383ss16/lab1 folder</li>

 <li>Change your working <u>directory</u> to be <em>lab1</em></li>

 <li>Start capturing your session into <u>file</u> <strong>lab1</strong></li>

 <li>Display the contents of file lab1.1</li>

 <li>Display the contents of file lab1.2</li>

 <li>Display the contents of file lab1.3</li>

 <li>Stop the session recording</li>

 <li>Submit the file <strong>lab1</strong> thru Blackboard</li>

 <li>Submit the file <strong>script</strong> thru Blackboard</li>

</ol>




<strong>Part I Activities</strong>




It can be hard to remember all the commands and how to use them. The Unix operating system comes with a built-in manual (<strong>man pages</strong>) so that you can look up the details for how to use each command. Additional help facilities offered by Linux are the <strong>info</strong> command and the <strong>–help</strong> option.

This part of the lab is intended to give you practice using these commands. While it is possible to answer the below questions using Internet search engine, you are required to use <u>only</u> man pages, info command, and/or –help option.

For each question, you must give an answer as well as the source of your answer. For example, man page (or section) 2, info page, etc.

To answer the questions, follow the steps below:

<ul>

 <li>Log into the lab computer with your asurite username and password</li>

 <li>Change your working directory to IFT383ss16</li>

 <li>Start capturing your session under filename <strong><em>script</em></strong></li>

 <li>Create the file <strong><em>1</em></strong> and type in your answers to the questions below. When this file is displayed with the <strong>cat</strong> command, <u>the lines should be numbered</u>, each number corresponding to the question number. (8 pts)</li>

</ul>




<ol>

 <li>Use the manual pages to explain the use of the following <strong>man</strong> options: man –h; man –k; man –a; and man –f</li>

 <li>The command <strong>passwd</strong> is documented in more than one man page or section. Find out those section numbers.</li>

 <li>The default output from the <strong>man</strong> command is the first manual page found. How do you force <strong>man</strong> to display all the manual pages for a particular command?</li>

 <li> How do you ask <strong>man</strong> to display the entry from a particular section; for example displaying the entry from section 3p for the command <strong>mkdir</strong>?</li>

 <li>What should the command “<strong>cat lab1.1 – lab1.2</strong>” do?  (Don’t try to run it, just figure it out from the documentation.  Assume <em>lab1.1</em> and <em>lab1.2</em> are existing files.  Note the spaces and the dash in the command line.)</li>

 <li>What three options to the <strong>date</strong> command can be used to display the current date and time in <em>Coordinated Universal Time</em>?</li>

 <li>The command <strong>man</strong> usually contains far more information about a command than you need. The commands<strong> info</strong>, <strong>apropos</strong>, or <strong>–help</strong> could be more helpful. Which of these can give you a quick guide to printing the current month name (eg. January) using the date command?</li>

 <li>Which man page section provides documentation for the command  <strong>uname</strong> as used to obtain <em>the “name and information about the current kernel”</em> ?</li>

</ol>




<ul>

 <li>Terminate your session recording</li>

</ul>




<em>Now that you know how to get help, put it to use in Parts II &amp; III below.</em>




<strong>Part II Activities</strong>




Suppose you’re using your lab UNIX system to write a project summary report, “lab1.2.r” that must not exceed a specified number of words.

The approximate series of events that might take place is shown in the table below. For each step listed in the “Steps” column, you’re to provide the appropriate command in the “Commands” column. You must use <strong><em>only those commands covered so far</em></strong>.

To answer the questions, follow the steps below:

<ul>

 <li>Log into the lab computer with your asurite username and password, if you’re logged off</li>

 <li>Change your working directory to IFT383ss16, if you’re not there</li>

 <li>Start capturing your session under filename <strong>script</strong>, <em>appending</em> to the previous recording</li>

 <li>Create the file lab1.2 and type in your answers to the questions below. When this file is displayed with the <strong>cat</strong> command, <u>the lines should be numbered</u>, each number corresponding to the question number. <u>Don’t just type the commands</u>, make a complete sentence that includes the command surrounded by grave-accents. For example, if the first step says: <em>“you write today’s date and time”</em>. Your answer could be something like: <em>“The current date and time is `<strong>date`</strong>” </em>(12 pts)</li>

</ul>




<table>

 <tbody>

  <tr>

   <td width="415">Steps</td>

   <td width="129">Commands</td>

  </tr>

  <tr>

   <td width="415">1.     You write the date in the format “January 20 2015”</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">2.     You displayed your current working directory</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">3.     You go to your IFT383ss16 directory</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">4.     You listed the directory contents to see the size of the file</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">5.     You display the content of “lab1.2.r” file</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">6.     You rename it as the first draft “lab1.2.r1”</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">7.     You create a subdirectory called “lab1” to store the first draft</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">8.     You move “lab1.2.r1” into the “lab1” subdirectory</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">9.     You make a copy of “lab1.2.r1” and call it “lab1.2.r2”</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">10.  After editing “lab1.2.r2”, you rename it as “lab1.2.r.final”</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">11.  You remove the file “lab1.2.v1”</td>

   <td width="129"> </td>

  </tr>

  <tr>

   <td width="415">12.  Finally, you count the words in “lab1.2.r.final”</td>

   <td width="129"> </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Terminate your session recording</li>

</ul>

<strong>Part III Activities</strong>




As a system administrator in your organization, you need to perform some urgent maintenance tasks. It would require shutting down the system, which could cause those still logged in to lose some of their work. Mindful, you go through the series of events listed in the table below. For each event in the “Events” column, provide appropriate commands in the “Commands” column. You must use <strong><em>only those commands covered so far</em></strong>.




To proceed, follow the steps below:

<ul>

 <li>Log into the lab computer with your asurite username and password, if you’re logged off</li>

 <li>Change your working directory to IFT383ss16, if you’re not there</li>

 <li>Start capturing your session under filename <strong>script</strong>, <em>appending</em> to the previous recordings</li>

 <li>Create the file lab1.3 and type in your answers to the series of events below. When this file is displayed with the <strong>cat</strong> command, <u>the lines should be numbered</u>, each number corresponding to the appropriate event. <u>Don’t just type the commands</u>, make a complete sentence that includes the command surrounded by grave-accents. For example, the first step says: <em>“you decide to record all your actions under the file lab1.3”</em>. Your answer could be something like: <em>“All my actions are being recorded under lab1.3 file `<strong>script lab1.3`</strong>” </em>(8 pts)</li>

</ul>




<table>

 <tbody>

  <tr>

   <td width="433">Events</td>

   <td width="126">Commands</td>

  </tr>

  <tr>

   <td width="433">1.     First of all, you decide to record all your actions under the file “lab1.3” just in case…</td>

   <td width="126"> </td>

  </tr>

  <tr>

   <td width="433">2.     Next, you find out who is still using the system.</td>

   <td width="126"> </td>

  </tr>

  <tr>

   <td width="433">3.     Since your closest neighbor (either right or left) is logged in, you sent him/her the following short message “Hi, please save your work and logout now, system maintenance”</td>

   <td width="126"> </td>

  </tr>

  <tr>

   <td width="433">4.     You’re not having any response and decide to get more information about that user</td>

   <td width="126"> </td>

  </tr>

  <tr>

   <td width="433">5.     Then you list all the active processes running on the machine</td>

   <td width="126"> </td>

  </tr>

  <tr>

   <td width="433">6.     Finally, you kill the processes associated with his/her terminal. Indicate how you determine the ID</td>

   <td width="126"> </td>

  </tr>

  <tr>

   <td width="433">7.     Now you stop capturing your session</td>

   <td width="126"> </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Terminate your session recording</li>

</ul>


