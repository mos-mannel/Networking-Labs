## PROJECT
Automating network provisioning with DHCP Services

## OVERVIEW
 
 * Problem: 
  - Up until this point, you have had to click on every single computer and manually type in it IP address and subnet mask. In a business with hundreds of devices, phones and laptops constantly moving around, managing a manual spreadsheet of IP addresses is completely impossible 

 * Solution: 
  - This project introduces Dynamic Host Configuration Protocol (DHCP). Instead of manually addressing every host, we will deploy a central network server that automatically assigns IP addresses, subnet masks, and other crucial network information to any device the moment it plugs into the network.

## TECHNOLOGY USED 
 - Dynamic Host Configuration Protocol (DHCP)
 - DORA (Discover, Offer, Request and acknowledge) broadcast sequence
 - IP scope exclusive design 
 - Automatic Private IP Addressing (APIPA) diagnostic containment
## CONFIGURATIONS 
 - Configured a server with a static IP address before it can distribute configuration variables to our devices.
 - Build and activated the DHCP service engine
 - Configured the endpoint devices to use dynamic provisioning
 - Verified and Tested Endpoints for success

## DESIRED OUTCOMES
  - A plug-and-play local network environment where hosts dynamically acquire valid IP identities instantly upon physical link validation. 