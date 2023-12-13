<p align="center">
<img src="https://i.imgur.com/NyD7nEg.png" height="80%" width="80%" alt="AirTable"/>
</p>

<h1>Automating Communication From AirTable to Slack</h1>
In this tutorial, we observe the confirmation of a bill being paid and it being announced in Slack. <br />

<h2>Environments and Technologies Used</h2>

- AirTable
- AirTable Automations
- Slack
  
<h2>High-Level Steps</h2>

- Step 1: Create the fields needed
- Step 2: Create the automation
- Step 3: Test the automation

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/COxH73U.png" height="80%" width="80%"/>
</p>
<p>
The five fields that I found to be of importance are highlighted above. NOTE: I used the Confirmation Code field as the trigger - this info will come in handy later.</p>
<br />

<p>
<img src="https://i.imgur.com/dPkIvK9.png" height="80%" width="80%"/>
</p>
<p>
For the conditions of the trigger, observe the configuration displayed above.
</p>
<br />

<p>
<img src="https://i.imgur.com/VENhq0i.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/rRVz82g.png" height="80%" width="80%"/>
</p>
<p>
For the Slack message configuration, this is what the syntax should look like. 
</p>
<br />

<p>
<img src="https://i.imgur.com/k89dv7K.png" height="80%" width="80%"/>
</p>
<p>
Save the changes and run the test. It should look like this.<br>
  <br>
In the future, you only have to change out a couple of fields when updating the system. I leave the confirmation code blank until the payment is made, then I add the code and that signals the posting to Slack. Enjoy.
</b>
</p>
<br />
