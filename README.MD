# How to setup
1. Download the source file (.zip)
2. Extract the file.
3. IMPORTANT: Stop the IIS Web and IIS Apppool of the site.
4. After extracting the file, there are 2 folders named: "asset-management-sln" and "publish". The section below describes the steps for each folder:
   - asset-management-sln
     - In the server, delete all files in the "asset-management-sln" folder.
     - In our local machine, copy the new files we just extracted in the "asset-management-sln" folder to the "asset-management-sln" folder in the server.
   - publish
     - We simply copy and override all the files from source to server folder, without deleting anything. When pasting, please choose the "Copy and Replace" option.
5. Database: if there is a script .sql file in the zip folder, run this script against the production database.
6. Start IIS and IISApppool again
