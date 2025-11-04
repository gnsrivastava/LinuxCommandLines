# Common commands used by any linux user daily

1. **List [```ls```]** <br>
   Users can run this command by typing ```ls``` in their terminal.<br>
   - List command (```ls```) is used to list all elements (files or folders) in a directory (folder).
   ```bash
   ls
   ```
   There various useful options that users of Linux employ to make ```ls``` command output intuitive and informative. <br>

   **a) Command to list files based on date of creation**
   ```bash
   ls -ltrh
   ```
      - Above command returns the list of items as above but with the additonal information about the permission, user who created these files, file size in human readable format (Mb or Gb) and date the file was created.
      - ```ls -ltrh``` can be useful when you want to see which is the **most recent** file that you as a user have created and what are the details of that file.<br>

   **b) List the files based on their file size**

   ```bash
   ls -lhS
   ```
     - The above commands lists all the files in a folder after sorting them by their size in discending order from ```Largest``` to ```Smallest``` files. 
