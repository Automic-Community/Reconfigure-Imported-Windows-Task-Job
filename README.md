*Reconfigure Imported Windows Task Job*
=============


This script can be used to replace some part of the script of the imported Jobs.
http://github.com/Automic-Community/Reconfigure-Imported-Windows-Task-Job

<!-- List of attached files -->
Contents of Solution Package:

						
								*Windows_Task_Scheduler-Reconfigure.zip
								
						


Documenation and Instructions
---

<p><span><strong class="bbc">Description</strong></span><br />&nbsp;<br />Dollar Universe and UniJob can import job from Windows Task Scheduler. The command is imported "as it is" in Dollar Universe/UniJob. Then sometimes it might be needed to adapt the job a little.<br />This script can be used to replace some part of the script of the imported Jobs.<br />&nbsp;<br /><span class="bbc_underline">Note</span>: as not all job might have to be modified, there is a parameter to filter which job have to be updated.<br />&nbsp;<br />&nbsp;<br /><strong class="bbc"><span>Procedure</span></strong></p>
<ul class="bbc">
<li>​Rename the .txt to .bat​</li>
<li>Update the script to set the parameter&nbsp;M_FILTER_JOB (this should contain part of the name of the jobs to be updated)</li>
<li>Create a UniJob Job and
<ul class="bbc">
<li>Add this file in the Job</li>
<li>Call the script in the command of the Job</li>
</ul>
</li>
<li>Execute the job (this should then update all imported job accordingly)</li>
<li>Test the jobs again and validate that it's now working</li>
</ul>
<p>Once the solution is validated, it is possible to:</p>
<ul class="bbc">
<li>​Update the schedule of this job (if it has to be executed regularly or just once)​</li>
<li>Add this job to a package</li>
<li>Deploy the package to all nodes</li>
</ul>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
