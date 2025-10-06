# AutomatedTestingTools
The required test case scenarios are converted into pseudo steps for test automation. Script functionalities can be categorized into GUI-based actions and Non-GUI actions.

GUI actions are performed based on the IDs of each control, which can be identified using tools such as UI Spy or UIAVerify provided by Microsoft.

Non-GUI actions, such as retrieving information from the test system or simulating hardware and operating system operations, can be implemented using WMI (Windows Management Instrumentation) or Win32 Classes provided by Microsoft.

WMI provides an infrastructure for managing data and operations on Windows-based systems. WMI scripts can be used to automate administrative tasks on local or remote computers.

Win32 Classes are categorized into several types, such as Computer Hardware Classes, Operating System Classes, Performance Counter Classes, and Installed Application Classes, which can be used to retrieve information or simulate hardware functions.

Once the test scripts are created, they need to be validated against specified machine profiles. This ensures that all necessary components are in place for successful test execution before storing the scripts in the centralized database for unified distribution across locations.

Test coverage includes the following areas:
<ul>
  <li>Network connectivity – Transfer speeds</li>
  <li>USB transfer rates and Bluetooth connectivity</li>
  <li>Display settings – Change and verification</li>
  <li>Power management – Continuous operation simulations</li>
  <li>User scenario testing – Simulation of end-user actions</li>
  <li>GUI testing – Verification of application settings</li>
</ul>
<img width="693" height="652" alt="ats" src="https://github.com/user-attachments/assets/4cc41124-1146-4063-b432-50f3210ded3e" />
