# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:

#### Name - Kantha Sishanth S
#### Reg. No. - 212222100020

### CREATING A DISK PARTITION:

#### Step 1: Open File Manager
```
Right-click This PC → Click Show More Options.

Select Manage.
```
#### Step 2: Access Disk Management
```
In the new window, select Disk Management.
```
#### Step 3: Shrink the C Drive to Allocate Space
```
Locate C: drive → Right-click → Select Shrink Volume.

Enter the amount of memory to allocate for the new disk.

Click Shrink.
```
#### Step 4: Create a New Volume
```
Right-click on the newly unallocated space → Select New Simple Volume.

Follow the wizard and assign a disk name.

Click Finish to complete the process.

The new Disk Partition is created
```

<img width="1920" height="496" alt="Screenshot 2025-08-22 132826" src="https://github.com/user-attachments/assets/dbc29d80-e87f-46f8-83a1-a521c0ae8f54" />



### ANALYSING FILES USING AUTOPSY:

#### Step 1: Create a Case
```
Enter a case name and select a location to store the case data.

Provide a case number and investigator details if required.
```
#### Step 2: Add a Data Source
```
Click "Add Data Source" and choose the type:

Select the data source and let Autopsy process it.
```

#### Step 3: File Analysis

##### Application

<img width="1920" height="982" alt="Screenshot 2025-08-22 091716" src="https://github.com/user-attachments/assets/6b956ce4-d463-4bdd-8c40-6942a4e295b5" />


##### File Metadata

<img width="1368" height="823" alt="Screenshot 2025-08-22 131835" src="https://github.com/user-attachments/assets/3429099b-cbb5-489a-803b-a644be279a90" />


##### Click OS Account.

<img width="1342" height="793" alt="479609176-c77c21e9-6fdc-4cd7-958a-c904cb6b23dc" src="https://github.com/user-attachments/assets/ad7d4ab7-e628-4c9e-9419-cde117493330" />


### GENERATE REPORT:

<img width="1920" height="751" alt="Screenshot 2025-08-22 093434" src="https://github.com/user-attachments/assets/ccad97be-c182-45cc-8c7d-cc0019a2e18b" />


## RESULT:

Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
