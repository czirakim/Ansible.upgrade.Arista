<snippet>
  <content>

## Ansible.upgrade.Arista

The scope of this project is to automate the process of upgradeing Arista switches.
<br>The upgrade will take place only if some conditions are met, like :
<br>MLAG status is active, there is enough disk space, the MD5 checksum is valid,
<br>the current image version does not match the target version.
 

## Usage

The project is made of a main yml file , a vars file and an inventory file.
<br>In the vars file I've defined how we connect to the switches (api and cli),
<br>and also the target version, the url from where we download the image file etc.
<br>The main file contains all the tasks. 

  
## Credits
This was written by Mihai Cziraki
</content>
</snippet>
