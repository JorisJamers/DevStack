# Documentation Cloud&Automation
## Devstack

Devstack is a way to provide and maintain tools used for installation of the central OpenStack services from source suitable for development and operational testing. It also demonstrates and documents examples of configuring and running services as well as command line client usage. 

DevStack is an opinionated script to quickly create an OpenStack development environment. It can also be used to demonstrate starting/running OpenStack services and provide examples of using them from a command line.

### Installation

These few steps will install a complete devstack on your own system. 

1. We need to add a new "stack" user to the system before we begin the installation. 

![alt text][image1]

[image1]: https://user-images.githubusercontent.com/26601353/34482932-97cac246-efbb-11e7-8ef0-f711ac7be5ad.png "Add new user"

2. The newly added user will need sudo privileges because he is going to make many changes to our system. Afterwards we change ourself to the stack user. 

![alt text][image2]

[image2]: https://user-images.githubusercontent.com/26601353/34482938-9c130160-efbb-11e7-99d1-6791e7381a2b.png "Sudo rights"

3. When we became the stack user we are ready to download DevStack from github. And we enter the folder "devstack". 

![alt text][image3]

[image3]: https://user-images.githubusercontent.com/26601353/34482939-9efafe1e-efbb-11e7-80f4-a35bab6262ed.png "Download devstack"

4. If you completed all the steps above you are now able to make a "local.conf" file in the folder "devstack". The config file should look like this. 

![alt text][image4]

[image4]: https://user-images.githubusercontent.com/26601353/34482942-a3cf5aa2-efbb-11e7-86fd-8009a3ed35b2.png "Local.conf content"

These are the minimum required configs to get started with DevStack 

5. At this moment you can start the DevStack install. This will take about 15 - 20 minutes on a decent internet connection. Otherwise it could take even 40 - 50+ minutes. Many git trees and packages will be downloaded and installed. 

![alt text][image5]

[image5]: https://user-images.githubusercontent.com/26601353/34482944-a679c076-efbb-11e7-9001-c8c82ac930cf.png "Install commando devstack"







