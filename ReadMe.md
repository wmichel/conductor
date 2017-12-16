# WHAT IT IS
The goal behind Conductor is to become the IFTTT for the data center. Think vRO for the simple man. Conductor is uses Events and Actions. Based on an event, you can trigger an action (or chain actions together).

Some examples of Events:
+ Log Insight alert (file system full)
+ vROPS alert (High CPU)
+ Webhook from an upstream workflow
+ Straight up API call

Some examples of Actions
+ Text/Email someone
+ Snapshot/Pause/Delete a VM
+ Add an NSX Security Tag
+ Delete oldest Snapshot

The goal is also to make this a pluggable framework based on Docker containers. Anyone can create an Action. They just need to define the various Environment Variables to pass into a container, and the container's location.

# MVP
The Minimum Viable Product we are aiming for is a Log Insight alert that triggers a text message to my cell phone.

#Stretched Goals
+ Create more Actions
+ Create a GUI front end
+ Look to turning Events into Docker containers
