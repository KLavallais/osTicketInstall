# **Installing osTicket on a Virtual Machine (Microsoft Azure)**

[![Watch the Full Video](https://github.com/KLavallais/KLavallais/blob/assets/osTicket%20Installation%20Thumbnail.png)](https://www.youtube.com/watch?v=5FxwlTwsrdk)


## **Summary:**
In this video, I walk you through the installation of osTicket on a virtual machine that I have set up in **Microsoft Azure**. The process includes configuring the web server (IIS), setting up PHP, and installing MySQL. I provide step-by-step guidance while removing unnecessary parts to keep things as concise as possible.

This guide highlights the foundational steps to get osTicket running. A follow-up video and repository will cover post-installation configurations, where I will focus on the settings you need to make after osTicket is installed.

## **Technologies/Tools Used:**
- **Microsoft Azure**: For setting up the virtual machine.
- **osTicket**: The help desk ticketing system being installed.
- **Internet Information Services (IIS)**: Windows web server setup.
- **PHP**: Used for osTicket to run properly.
- **MySQL**: Database used for osTicket.
- **HeidiSQL**: GUI to manage MySQL databases.
- **Visual C++ Redistributable**: Required for PHP.

## **Skills Displayed:**
- Setting up a virtual machine in Azure.
- Installing and configuring IIS.
- Installing PHP and its dependencies.
- Configuring MySQL.
- Troubleshooting osTicket installation issues.
- Using command-line tools and graphical interfaces to manage software.

## **General Steps in the Video:**
1. **Starting the Virtual Machine on Microsoft Azure**
   - Explanation of the VM setup process.
2. **Downloading osTicket Installation Files**
   - Downloading osTicket files on the virtual machine to expedite the process.
3. **Setting Up Internet Information Services (IIS)**
   - Configuring IIS for osTicket.
4. **Installing PHP Manager for IIS**
   - Adding PHP Manager to IIS to manage PHP installations.
5. **Installing MySQL Server**
   - Configuring the MySQL server with a simple root password for demonstration purposes.
6. **Configuring osTicket Installation**
   - Moving and renaming files and setting permissions.
7. **Creating and Setting Up the osTicket Database**
   - Using HeidiSQL to create a database for osTicket.
8. **Completing the osTicket Installation**
   - Final steps for configuring osTicket, including setting file permissions and testing the installation.

## **Post-Installation Repository:**
Once osTicket is installed, there are several settings to be configured for optimal performance, including user roles, departments, teams, service level agreements (SLAs), and help topics. I have created a separate repository that will guide you through all the necessary **post-installation settings** to ensure osTicket works as expected for your specific use case.

- **[Link to the Post-Installation Repository](https://github.com/KLavallais/osTicketPostSetup)**

This repository will include:
- **Configuring User Roles**: Assign roles with varying permissions.
- **Setting Up Departments and Teams**: Organize agents into departments and cross-functional teams.
- **Defining SLAs**: Set response and resolution times based on the priority of tickets.
- **Creating Help Topics**: Streamline ticket submission by creating predefined topics.

---

By following the steps in this video, you will have successfully installed osTicket. For further configurations and enhancements, please refer to the **post-installation repository** for detailed instructions.

