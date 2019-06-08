# The Azure 3 Tier Network
For the serious security concious, this is one way to do networks from within Azure. In brief, the T1 vNet can't talk directly with the T3 vNet and vice versa. 

<p align="center">
  <img src="AzureNetworkT1,T2,T3.jpg" width=80%>
</p>

## Azure-T3-Network
This repo is for the Tier 3 part of the 3 tier network.

<p align="center">
  <img src="AzureNetworkT3.jpg" width=80%>
</p>

To deploy the most trusted T3 bottom layer of this Azure network:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmarckean%2FAzure-T3-Network%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmarckean%2FAzure-T3-Network%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>