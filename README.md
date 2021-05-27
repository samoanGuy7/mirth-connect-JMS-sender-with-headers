# mirth-connect-JMS-sender-with-headers
Mirth Connect channel JMS sender with headers
To get this code to work, make sure you have a copy of activemq-all-x.x.x.jar

Steps
1) Load the jar in a resource folder in the mirth directory, and ensure that the jar file is picked up in the resource manager.
2) Set the dependencies on the channel that you intend to put the js sender on, making sure to include the resource with the activemq jar file inside of it.
3) On the Destination connector, set the type to javascript sender
4) Copy and paste the above code
5) Make sure to change variables to whatever you need for your configuration. 

Hope this helps!

