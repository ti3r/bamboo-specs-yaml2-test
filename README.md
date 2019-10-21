## Bamboo 6.10 yaml v2 spec test ##

Simple repository to test how bamboo-specs work with Atlassian Bamboo 6.10. This repository just simply builds a docker image containing 
mysql client. The main features of a spec required by ICF Nexts CICD pipeline are utilized in this repository. 
Several stages with several jobs that communicate with eachother using shared artifacts and variable that build a final executable docker image
ready to be used in our environments.

