Task 1: Incorporating new components in the Platform
Introduction
In this task, I have incorporated two new components in the eSim-Cloud platform - DHT11 sensor and 7447 decoder IC. I chose these two components because they are commonly used in many electronic projects and can provide useful functionalities.

Approach
I started by forking the eSim-Cloud repository to my GitHub account and creating a new branch 'add_new_components' from the Develop branch. I then added the required libraries for the DHT11 sensor and 7447 decoder IC to the libraries folder in the repository. I also made changes to the existing code in the components.js and componentData.json files to include the new components.

I followed the Spoken Tutorials linked in the task description to understand how to interface the components with the Arduino Uno and write the necessary sketch files (.ino). I used the Arduino IDE to write the code for the DHT11 sensor and 7447 decoder IC, tested it on a physical Arduino board, and then integrated the code with the eSim-Cloud platform.

Changes Made
The following files were changed heavily to incorporate the new components:

components.js - Added the DHT11 sensor and 7447 decoder IC components to the list of available components.
componentData.json - Added the DHT11 sensor and 7447 decoder IC data to the JSON object containing component information.
lib folder - Added the necessary libraries for the DHT11 sensor and 7447 decoder IC.
Demo
I have created a demo video showcasing the newly added components and their functionality. The video can be accessed at the following link: https://youtu.be/h-AWJFtzjAM

Release
I have tagged a release on GitHub with the following URL: https://github.com/melvin15may/eSim-Cloud/releases/tag/v1.0

Conclusion
I thoroughly enjoyed working on this task and learning about the new components. The eSim-Cloud platform provides a great way to experiment with electronics and I am excited to see what else can be built on top of it.