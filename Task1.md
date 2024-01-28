# 1.<u> Installation of Linux(Ubuntu)</u>




* ### <u>Accessing Linux on Your Devices</u>

  There are three main ways to use Linux on your computer:

  ### *1. Virtualization*

  - **What is it?**
  - Running Linux like a computer inside your current operating system (like Windows or macOS).
    
- **Popular Programs:**
    - VirtualBox, VMware, and Hyper-V.
    
  - **Benefits:**
    - Lets you try Linux without changing your computer.
    - Great for learning and testing software.
  
  ### *2. Windows Subsystem for Linux (WSL)*
  
  - **What is it?**
  - A feature from Microsoft that lets you run Linux inside Windows 10 or 11.
  
- **How it Works:**
    - Uses virtualization, but it feels like Linux is part of Windows.
    
  - **Ideal for:**
    - Developers who need both Linux and Windows tools.
    
  
  ### *3. Booting with Linux*
  
  - **What is it?**
  - Installing Linux directly on your computer, either replacing or working alongside your current operating system.
  
- **Considerations:**
    - More permanent, needs technical know-how.
    
  - **Best for:**
    - *Users who want Linux as their main system.*
  
  ## *About VMware, Inc.*
  
  - **What is it?**
  - A company that makes software for virtualization (like running multiple operating systems on one computer).
  - **Notable Achievements:**
  - First successful company to make virtualization work for everyday computers

# 2. <u>Installing Ubuntu with VMWare Player</u>:

**The steps involved are:**

* **Download and install VMWare Player.**

* **Download Ubuntu 12.04 LTS.**

* **Install Ubuntu with VMWare Player.**

  * ## Visualization with VM Player

  VM Player is like a magical computer inside your computer. Imagine having different worlds on your computer screen, all running at the same time!

  * ### What's Happening?

  - **Virtualization:**
    - VM Player creates separate little worlds, called virtual machines, inside your computer. Each world can be a different operating system, like having Windows and Linux both running on your computer.
  
  - **Host System:**
    - Your main computer system (like Windows) is the host. It's the boss overseeing everything.
  
  - **Guest Systems:**
    - The little worlds inside are guests. Each can be its own computer, doing different things without disturbing the others.
  
  * ###  How It Works:
  
  1. **Install VM Player:**
     - You install VM Player on your computer, like adding a new app.
  
  2. **Create a Virtual Machine:**
     - With VM Player, you make a new little world. You choose what operating system it will have, how much space it gets, and other settings.
  
  3. **Install Guest OS:**
     - You install an operating system inside this little world, just like you install Windows on your computer.
  
  4. **Run Multiple VMs:**
     - VM Player lets you run many of these little worlds at the same time. It's like having multiple computers inside your computer!
  
  ### 3. <u>Installing VMWare Player</u>
  
  * **Double click on the downloaded setup file to run installer and follow appropriate installations steps.**
  
    ### 4. <u>Downloading Ubuntu</u>
  
    * step1:
  
      **click this link to download Ubuntu!**
  
      [Download Ubuntu Desktop](https://www.ubuntu.com/download/desktop)
  
      ![image-20240126170953830](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126170953830.png)
  
  * Step 2:
  
    1.  **Open the VMWare Player.**
  
    2.  **Now Click the link "Click Virtual Machine".**
  
    ![image-20240126171140135](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126171140135.png)
  
  

* step3.

  ***Select Option Installer disc image file and click browse..***

  ![image-20240126171618537](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126171618537.png)

* step4.

  ***Select downloading 'iso' file for ubuntu and click "Next".***

  ![image-20240126171517837](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126171517837.png)

* step5.

  - ***fill in the required information & continue the installation***

    ![image-20240126171838954](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126171838954.png)

    

* step6.

  **Select the directory where files to be saved.**

  ![image-20240126172025680](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126172025680.png)

* step7.

  1. **Select amount of space for installation.**

     ![image-20240126172119639](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126172119639.png)

* step8.

  1. **Click "Customize Hardware" to see virtual machine configuration.**

     ![image-20240126172224600](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126172224600.png)

* step9.

  1. **Now set up amount of RAM for Virtual Machine.**

     ![image-20240126172310117](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126172310117.png)

* step10.

  1. **Once click "Finish" Ubuntu Installation will start.**

  2. **if you want to try Ubuntu live media without any installation click Ty Ubuntu else click "Install ubuntu" to continue installation**

     ![image-20240126172528057](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126172528057.png)

* step11.

    **Once installation done it will reboot and after     that you van enjoy it:**

  ![image-20240126172642101](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126172642101.png)

***Finally*!**

after all steps you see your installed software  like this 

![image-20240126172817937](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126172817937.png)

## 5. WSL(windows subsystem for Linux)

* Following are the WSL commands:

  ***command:  wsl --install***

  ![image-20240126173103163](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126173103163.png)

  Check which distributions are available

  ***Command: wsl --list --online***

  ![image-20240126173210660](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126173210660.png)

  Install a new distribution:

  ***Command: wsl --install <Distribution Name>***

  ![image-20240126173253134](C:\Users\abdul sattar\AppData\Roaming\Typora\typora-user-images\image-20240126173253134.png)

#  6.Dual Booting the device

Dual booting the device is a little bit complex and requires caution when doing so. We will not go into details in this section but for the students willing to explore this at their own risk can try the following link to view the step by step guide to dual boot their devices.

[Dual booting step by step guide](https://www.xda-developers.com/dual-boot-windows-11-linux/)

## <u>Compilers Installation</u>:

* Following compilers are used for C and C++ language:

  1. For C language: gcc

  2. Command: sudo apt-get install gcc

     

* For C++ Language: g++

  1.Command: sudo apt-get install g++

## GitHub repository Link:

[link](https://github.com/iqratariqq/OSLab)
