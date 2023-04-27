# IP_Repo_Tool
IP_Repo_Tool is a Python-based tool that allows users to check the reputation of IP addresses from multiple sources such as Virustotal, Xforce, and Abuseipdb. The tool is designed to provide users with domain and ISP information for the given IP address, making it easy to identify potential security risks.
The tool can be used by anyone who needs to check the reputation of IP addresses quickly and easily. It is especially useful for security professionals, network administrators, and IT professionals who need to monitor IP addresses for potential threats.
The tool takes less than 100 seconds to check the reputation of 10 IP addresses, making it a time-saving tool. Users can provide a list of IP addresses in an Excel sheet, and the tool will perform reputation checks for each IP address and provide the results in a new sheet within the same Excel file.
The tool is built using the Virustotal Python API, Xforce Python API, and Abuseipdb API, and can be customized to suit the user's needs. Users can configure the tool to use different APIs and customize the output format to suit their needs.
The tool is designed to be user-friendly and easy to use, even for users with limited technical skills. The results are presented in an easy-to-understand manner, making it easy for users to interpret and act on the information.
In addition to providing reputation checks for IP addresses, the tool also provides logging and error handling, making it reliable and robust. Users can rely on the tool to provide accurate and up-to-date information about the reputation of IP addresses.
Overall, IP_Repo_Tool is a valuable tool for anyone looking to monitor the reputation of IP addresses. It is fast, reliable, and user-friendly, making it an essential tool for security professionals, network administrators, and IT professionals.

# Steps to Run the Tool : 
1. Download the zip file named "IP_Repo" and extract it anywhere in your windows system
2. Under zip, you may find below mentioned files :
  * IP_Repo.exe : Main executable file with GUI containing input fields and will give the desire output
  * IP_File.xlsx : An excel file in which user will provide the IP values and after successful running of IP_Repo.exe, will provide output for the same. 
  * Readme : Description File
  * License : GNU License for the exe usage
3. As this exe file shows multiple API results, user need to have API Keys. 

Steps to get API key are as follows :
* VirusTotal :
  * Go to the VirusTotal website at https://www.virustotal.com/.
  * Sign up for an account by clicking on the "Sign in" button at the top-right corner of the page and then clicking on the "Create an account" link.
  * After creating your account, log in to VirusTotal and navigate to the "API" tab.
  * Under the "API Key" section, click on the "Get your API key" button.
  * Follow the instructions provided to generate your API key.     
  * Once you have generated your API key, copy it and keep it in a secure location as you will need it to use the VirusTotal API in your scripts or applications.

* AbuseIPDB : 
  * Go to the AbuseIPDB website and sign up for an account.
  * Once you are logged in, navigate to the "API" section in the menu bar and click "API Settings."
  * In the "API Settings" page, you will find your API key. Click on the "Create new API key" button if you don't already have one.
  * Enter a name for your API key and choose the desired permissions you want to grant to the key. 
  * Once you have selected your permissions, click the "Create API key" button.
  * Your new API key will be displayed on the page. Make sure to copy and save it somewhere secure, as it will not be displayed again.
  * You can now use your API key to access the AbuseIPDB API.
  
* IBM Xforce :
  * Go to the IBM X-Force Exchange website and click the "Sign In" button and log in to the IBM X-Force Exchange website.
  * Click on your profile icon in the top right corner of the screen, then select "API Keys" from the drop-down menu.
  * Click the "Create API Key" button.
  * Give your API key a name and select the appropriate access level.
  * Under "Access," choose the X-Force Exchange API that you want to use.
  * Click "Create API Key."
  * Your new API key will be displayed, along with a password. Be sure to copy and save the API key and password somewhere secure, as you will not be able to see the password again.
  * Use your new API key and password to access the IBM X-Force Exchange API in your application.
  
Note: There are both free and paid plans available for using the API's, and the process for obtaining an API key may vary slightly depending on the plan         you choose. 


4. Firsty, open the excel file "IP_File.xlsx" and put your IP's into the mentioned IP Columns as shown in screenshot and then save and close it.

5. Now run the downloaded exe "IP.exe", provide your Virustotal Auth Key, AbuseIPDB Auth Key, IBM Xforce Auth Key & password and File path (where IP_File.xlsx is stored) and click on the Calculate Button. Wait for result to load and then it will show some pop up message of completion. 

6. Check the file and user will get the desire result of the IP reputation from different portals with their domain and isp information. Also, incase of any error it will directly pop up out with error notification.
