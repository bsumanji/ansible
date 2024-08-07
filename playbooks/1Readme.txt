1. configure yum repository: ---------------------------------"yumRepoConfigure.yaml"

2. Upgrade Yum package: --------------------------------------"yumUpgrade.yml"

3. Install packages using yum: -------------------------------"yum-install-packages.yml"

4. Allowing Packages(using loops) in firewall: ---------------"yum-install-packages.yml"

5. Create, copy, rename, move both files and folder: ---------"copy_move_folder_files.yaml"

6. Host based service installation:  -------------------------"when_mount_installservice.yaml"

7. OS family based service installation:----------------------"whenDifferentOSfamilyInstallService.yaml"

8. Ansible Group based service installation: -----------------"whenSeperateGroupInstallService.yaml"

9. Changing service port of httpd: ---------------------------"servicePortChange.yaml"

10. Create users and groups: ---------------------------------"create-user-group.yaml"

11. Create files and folder with ownership, permission and then do all rename, copy, move files and folder to new directory:
-------------------------------------"create_file__directory.yaml" , "copy_move_folder_files.yaml"


12. Using Loops to create users and groups:-------------------"usingLoopsToCreateUsersNGroups.yaml"

13. Editing file:(add, insert, replace, comment, uncomment, delete lines) ----------------------------"fileHandlingSimple.yaml"

14. downloading file:-----------------------------------------"downloadingfiles.yml"

15. Creating cron Jobs: --------------------------------------"cronJobsMultiple.yml"

16. Archiving files: -----------------------------------------"archive-file.yaml"

17. Using debug,rescue, always:-------------------------------"physical-paritition-conditional.yml"


#####################################################################################
#################################### Partition ######################################
#####################################################################################


18. Mounting physical disk to system: ------------------------"mount-physicalDisk.yaml"

19. Physical Partition: --------------------------------------"physical-paritition.yaml"

20. Swap Partition: ------------------------------------------"swap-partition.yml" 

21. Multiple logical partition: ------------------------------"logical-partition.yml"

22. Logical Partition with extent: ---------------------------"logical-partition-extent.yml"

23. Conditional physical partiton:----------------------------"physical-paritition-conditional.yml"


#####################################################################################
############################ System Info And Security ###############################
#####################################################################################


24. Collecting hardware reports: ------------------------------"hwreport.yml"

25. Composing /etc/hosts file: --------------------------------"myhosts.yml"
