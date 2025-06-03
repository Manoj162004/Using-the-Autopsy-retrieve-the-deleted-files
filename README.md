# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.
## Open Autopsy & Create a New Case
Launch Autopsy and Run as a administrator
Click Create New Case.
![Screenshot 2025-04-06 220942](https://github.com/user-attachments/assets/372d41a3-9e5a-4e4d-ace5-7c669b1de4bf)
Enter a Case Name (e.g., Autopsy1).
Choose a Case Folder location.
Click Next → Click Finish.
![image](https://github.com/user-attachments/assets/86766ebc-30d7-42aa-b04c-506e83d4be0f)
## Add the Virtual Disk as an Evidence Source
Click Add Data Source → Select Host
![image](https://github.com/user-attachments/assets/f1eb327a-f2be-4785-ab7c-5741b3f3dfa4)

Select Local Disk → next
![image](https://github.com/user-attachments/assets/4fe19158-5f64-45e1-97f2-68c1d10d6f92)

![image](https://github.com/user-attachments/assets/ce310048-bca7-45eb-853e-75922b6ef781)
Click Next → Keep default settings → Click Finish.
Wait for Autopsy to process the disk.
## Recover Deleted Files
Go to File Views (left panel).
![image](https://github.com/user-attachments/assets/bc2fff06-38eb-453b-83a2-58e8ffb86a74)
Click Deleted Files → Find your deleted images.

Right-click an image → Click Extract File.

Select a folder to see the recovered files (e.g., C:\forensic).

Image is recovered successfully. 
![image](https://github.com/user-attachments/assets/0c423e81-74eb-49b1-9bd3-2405b2e42ebf)

![image](https://github.com/user-attachments/assets/53c3ad0e-2aef-49ef-81ac-7092c29aa2cf)



## PROGRAM:
Autopsy Deleted File Recovery Steps

## OUTPUT:
Recovered Deleted File List and Details
## Before Deleting:
![image](https://github.com/user-attachments/assets/b4cdbec8-b631-45f4-aac5-35325173274e)
## After Deleting:
![image](https://github.com/user-attachments/assets/a91ca298-7275-43bd-be36-fd55add050f4)
## After Recovering:
![image](https://github.com/user-attachments/assets/7d777f45-cae7-434b-9251-d19723e9e4b8)


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
