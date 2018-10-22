# SFDX  App Description
This sample snippit can be used to demostrate if worflow security and formula fields enforce field level security. 

## Dev, Build and Test


## Resources


## Description of Files and Directories
1 - Create new user
	sfdx force:user:create --setalias qa-user
3 - load data
2 - login as user and update have annual revenue greater than 1000000.  This user does not have read or edit access to the field but value is still updated.
3 - login as system administrator and check Internal Risk Rating = high

## Issues


