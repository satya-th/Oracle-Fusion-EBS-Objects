# Oracle-Fusion-EBS-Objects

## Check Print BI Template:
   - Basic Check BI Publisger Template, can be customized for customer in house check print needs.
   ### Features/Design:
    - Fixed Number of Remitance lines on check stub
    - Well aligned MICR Line, goes with most of the banks.
    
    
## 12.1 to 12.2 Retrofit Script
  - This Script provided basic structure to retrofix EBS code objects when upgrading form 12.1 to 12.2
  ### Features/Design:
    - This script should be run from new temporary staging directory (e.g. /RETROFIT), users can use any name.
    - This temporary directory should be outside of APPL_TOP  directory tree.
    - This script should be executed on APP TIER by DBA from ***applmgr*** OS user
    - This script will need SQLPLUS access and read access all APPL_TOP folders and sub-folders.
    - Initilize the enviornment before executing it
