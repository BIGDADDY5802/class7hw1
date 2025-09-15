# class7hw1

# Launching an ec2 instance:

- after logging into aws go to the search menu and type ec2
- select ec2 virtual servers in the cloud
- in network and security select security groups 
- create a security group: 
- name security group > select Inbound rules > Protocol HTTP > anywhere ipv4 > 0.0.0.0/0 >  {DO NOT TOUCH OUTBOUND RULES} create
After security group is created then select instances in the left pane
- click launch an instance
- name the instance > default selection on the instance type
- skip keypair for now
- default vpc > select existing security group
- in the drop down menu select the security group you created (You can use the security group multiple times so keep it for later provisioning)
- select the advanced details drop down menu > scroll all the way down to the bottom where it says user data
- paste the simple.sh
- select launch instance

Teardown:
        - In left pane select instances
        - check the instance box to highlight the instance
        - click the instance state section in the top right of the screen
        - in the drop down menu select terminate instance

        <https://docs.google.com/document/d/1XXdrHTIUsvamxpHxvyJSbRpoACp6bcomYMhEpsX9VTw/edit?tab=t.0>

        With pictures ^