# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit

## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**

1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version


## OUTPUT:

#### Name - Sakthivel R
#### Reg. No. - 212222100044

### VIRTUAL BOX:

<img width="1806" height="998" alt="433006963-16145c2a-2d23-4ce3-98b3-782704b51d21" src="https://github.com/user-attachments/assets/d9e340b6-d93a-4eaf-a1db-dc8db56f7787" />


### KALI LINUX:

<img width="1920" height="988" alt="Screenshot 2025-08-13 090759" src="https://github.com/user-attachments/assets/d876eda1-0013-4c4b-9988-bebf8806f53d" />



### SLEUTH-KIT:

<img width="1920" height="357" alt="Screenshot 2025-08-13 090905" src="https://github.com/user-attachments/assets/376c83a2-d97c-4c2e-9108-bc29f20abbe5" />


## RESULT:

The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
