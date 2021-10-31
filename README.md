# my-aspire-project
I. Required Tools
  1. Java JDK (1.8 or above)
  2. IntelliJ - community edition
  3. Chrome
  4. ChromeDriver
II. Additional Tools
  1. Maven
  2. Selenium WebDriver
  3. JUnit
III. Setup the Application/Environment
  1. Download my_Aspire_project.zip and extract it (Ex: D:\my_Aspire_project\)
  2. Launch IntelliJ
  3. File > Open ... and browse to location that contains the extracted files/folders (Ex: D:\my_Aspire_project\)
  4. Select the "start" folder (Ex: D:\my_Aspire_project\start)
  5. After project is opened, select File > Project Structure...
  6. Select Modules, at Sources tab, select the root tree folder location (Ex: D:\my_Aspire_project\start) and select Mark as: Sources for all folders.
  7. Navigate to Dependencies tab, change the Scope to "Compile" for 2 libraries: Maven: junit:junit:4.12, Maven: org.hamcrest:hamcrest-core:1.3
  8. Then click Build > Build Project (Ctrl+F9) to build the project.
  9. Navigate to Project left panel > start > test > Form.java
  10. Run 'Form'
  
  More info: In this project, I just do the automation test for login, enter  OTP, select business role, additional details and get the last page text.
  
  IV. Aspire_Requirements_High_level_TCs.xlsx: Analysis requirements and breakdown the high level test cases for testing.
  
  
