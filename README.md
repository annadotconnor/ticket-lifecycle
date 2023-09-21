<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/lXn13tT.png">
</p>
<p>
Welcome to osTicket, or if you're here from the previous lab, welcome back :) If you would like to view the previous lab, please <a href="https://github.com/annadotconnor/osticket-setup">click here</a>. We will start at the agent dashboard. Throughout this lab we will demonstrate the support ticket life cycle, from user creation of a support ticket, to agent resolution. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/htFmczR.png">
</p>
<p>
Click Open a New Ticket, and choose one of the users you previously created. Choose Business Critical Outage as the topic, and you can choose your scenario or use what I have entered above. Scroll down and hit Create Ticket.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/eGXb1ap.png">
</p>
<p>
Confirmation of the ticket has been submitted. We  will continue making a couple more tickets to demonstrate, please click Open a New Ticket once again.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/QzsOjHf.png">
</p>
<p>
Just as before, choose a user you created, update the Help Topic as shown above, and enter the details. Click Create Ticket.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/mz33bLf.png">
</p>
<p>
One more ticket, please repeat the process following the guidelines shown.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/RizHNKc.png">
</p>
<p>
Now that we have support tickets created we will log out, and log back in as one of our agents to work the ticket.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/HjlaXMd.png">
</p>
<p>
Please enter the username and password credentials you created for your agent. If you username does not work, try the email you created for that agent. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/MWHp1Pb.png">
</p>
<p>
We are now in Jane's dashboard. If Jane were a real support agent, this is what she would see at the start of her work day. All users are shown that submitted suport tickets, and currently all tickets are at a "Normal" priority level. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/PMXDIX6.png">
</p>
<p>
From here Jane will begin to assign the tickets to either herself or other agents in the department as well as update the priority level and SLA.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/TYoh0ih.png">
</p>
<p>
Jane has chosen to assign the first ticket to herself. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/huZjkjR.png">
</p>
<p>
She will now assign the SLA.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/spIezJv.png">
</p>
<p>
She has determined this is a business impacting event, and appropriately chosen SEV-A.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/iKFU5Ee.png">
</p>
<p>
She must now assign this ticket to a Department.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/vVIs1Nw.png">
</p>
<p>
She has updated this ticket to System Administrators as this would be an elevated urgency, and the subject matter is the responsibility of the Sys Admins. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/K36COBV.png">
</p>
<p>
She will then properly document her updates within the ticket. Hit Post Reply.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/AT1mP2V.png">
</p>
<p>
In a live enterprise setting we would need to initiate research to find the issue, but for the sake of this lab we will say Jane found the issue, and is ready to move forward. Please click the Ticket tab and the ticket as shown. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/qWiRQQm.png">
</p>
<p>
Resolution is documented and the Ticket Status drop down is updated to "resolved". This will move the ticket out of Jane's dashboard. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/Fz0krS4.png">
</p>
<p>
As we can see the ticket is now resolved, and no longer showing in Jane's dashboard to be worked. We will move on to the next ticket.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/Ejw45Q4.png">
</p>
<p>
The next ticket will be assigned to our Support team member, John. This ticket is a SEV-B, High Priority. It's always good practice to reach out to your team member to let them know they are being assigned a ticket. This is called a warm handoff.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/CYz2IjI.png">
</p>
<p>
Proper documentation of the updates have been entered by Jane regarding assigning the ticket to John to be worked.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/3IjCE8I.png">
</p>
<p>
We can see that this ticket is now in Jane's dashboard set to high priority, and assigned to John. It will remain here until an administrator has closed the ticket.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/AbSWXBh.png">
</p>
<p>
For our last ticket Jane has assigned this to herself, updated SLA to SEV-C, and set priority level to low as appropriate.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/TY8B5ey.png">
</p>
<p>
This ticket can be resolved with a simple update, as shown above. Ticket Status has been updated to "Resolved", and we're able to move on.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/SpInewa.png">
</p>
<p>
As we can see the one remaining ticket is what we previously assigned to John. Go ahead and hit Log Out in the upper right corner. We will now move forward as our support agent John Doe.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/d8cShLf.png">
</p>
<p>
Login using the credentials you made for your second agent. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/UH6ozjh.png">
</p>
<p>
And here we can see the ticket is displayed in John's dashboard.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/w6ru1cN.png">
</p>
<p>
One we click into the ticket we can see the original ticket message submitted, as well as the updates left by Jane.
</p>
<br><br>


<p>
<img src="https://i.imgur.com/AwfmRDy.png">
</p>
<p>
Once again in a live setting we would need to initiate research to troubleshoot the issue, but for this lab we will move forward as John as resolved the problem. Proper documentation has been made. The Ticket Status remains open as the Support team does not have permissions to close tickets. Click Post Note, and once you are back on John's dashboard click Log Out in the upper right corner. 
</p>
<br><br>


<p>
<img src="https://i.imgur.com/JXDGRBb.png.png">
</p>
<p>
We will now login as our Sys Admin, and check John's progress.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/ltQbuuF.png">
</p>
<p>
We can see John's ticket is open in our Admin panel. We will review John's progress.
</p>
<br><br>


<p>
<img src="https://i.imgur.com/6Zu8gdM.png">
</p>
<p>
  We can see John successfully rolled back the software update, and the department is back up and working. Though John is looking into why the new update may have caused an outage, we can go ahead and close his ticket for him since the root issue has been resolved. The Ticket Status will be set to resolved. 
</p>
<br><br>
  
<p>
<img src="https://i.imgur.com/4ntdQaD.png">
</p>
<p>
 All tickets have cleared. This concludes our osTicket Life Cycles demonstration. 
<br><br>

