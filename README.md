# TimeTracker-Application

AUTHOR:

Lucian Sandile Young
Student Number: ST10039287
Email: luyoung247@gmail.com
ALT email: st10039287@vcconnect.edu.za

----------------------------------------------------------------------------------------------------
INTRODUCTION:

This android studio app is a time tracker application. A time tracker application designed to help its users track the time spent on various tasks, projects, or activities.
Thus, this application is intended to aid user productivity.

----------------------------------------------------------------------------------------------------
PURPOSE:

The purpose of this particular time tracker application is to help it's users track the progress they make for their projects. These projects can vary depending on the users
needs, therefore making the app flexable for a wide variety of users.

----------------------------------------------------------------------------------------------------
BUILT WITH:

Development platform: Android Studio Giraffe // 2022.3.1
Cloud-hosted database: Firebase Database (Using Firebase Authentication & Realtime Database)

----------------------------------------------------------------------------------------------------
SAMPLE USER DATA:

To use an already-existing account with data entered:
Email - admin@admin.com
Password - admin1234
*note that the data saved is as recent as 2024-05-03*
- Take this into consideration when using the date ranges for the analytics page.

To create a new account, optionally use:
Email - test@test.com
Password - test1234

...or use your own personal or self-created information.

----------------------------------------------------------------------------------------------------
PREREQUISITES:

It is highly recommended that the application is executed using the specifications that iT was created in. Below is a list of the software used to develop the application, that is best suited to use:

Desktop - Android Studio Giraffe // 2022.3.1 or higher

Include in the source code and in a separate folder is the application APK. This can be used within the context of the following devices for optimal performance:

Device  - Any android device with API 27 or higher.
	- Application was developed on a Google Pixel 5 device, thus this device or higher is best to operate on.
 
----------------------------------------------------------------------------------------------------
INSTALLATION:

Desktop Installation - running the source code...
- To download Android Studio Giraffe // 2022.3.1 or higher on your desktop, follow the steps below:

	step 1: search "Android Studio Download", choose the first link, then navigate to the Downloads page. 
	Or copy this URL: https://developer.android.com/studio?_gl=1*8y0ha5*_up*MQ..&gclid=Cj0KCQjwltKxBhDMARIsAG8KnqXqPEWGzVQPYzY8uQm79QI5soM0kwuKVcu-1FnmXRnxgjhsEgBWXVsaAk1kEALw_wcB&gclsrc=aw.ds

	step 2: select the "download archives" hyperlink option within the "More downloads avaiable" option.

	step 3: Agree to the terms and conditions of the android studio development platform.

	step 4: Download the installer for the Android Studio Giraffe | 2022.3.1 Patch 4 November 16, 2023

	step 5: Use the installer to install Android Studio Giraffe // 2022.3.1

	step 6: Ooen the development platform and use it to open the source code of the TimeTracker application.


Android Device Installation - download the APK...

	Step 1: Enable Installation from Unknown Sources
	To install APK files that aren't from the Google Play Store, you need to enable installation from unknown sources on your Android device:

	Open Settings: Go to the settings app on your Android device.
	Navigate to Security/Privacy: Depending on your Android version and device, this might be under "Security," "Privacy," or "Apps & Notifications."
	Enable Unknown Sources: Find "Install unknown apps" or "Unknown sources." Select the app (usually your browser or file manager) that you'll use to download the APK and enable the option to install from unknown sources.

	Step 2: Download the APK  file to your device. Click the download link, and the file should save to your "Downloads" folder or another designated location.

	Step 3: Install the APK File and follow the prompts to complete the installation. Once the installation is complete, you should see the app's icon in your app drawer or on your home screen.

	Step 4: Launch the Time Tracker App, from your app drawer or home screen.
	
	Alternative:The app can be opened on your desktop and downloaded directly onto an android decevice that is connected to it, ensure step 1 is completed first before doing this.
----------------------------------------------------------------------------------------------------
RUNNING THE APPLICATION:

After installing the application through the three options above the application can be run on a desktop with the use of an emulator through the android studio platform.
If the application has been downloaded on a device, then it can be run by simply selecting the applciation icon on the menu of the device.

Once running, the application will require the user to either sign up or sign in. All data is connected directly to a live Firebase Database.

----------------------------------------------------------------------------------------------------
FUNCTIONAL REQUIREMENTS:

1. User Registration and Authentication
	User Registration: The ability for users to create accounts with personal information like name, email, and password.
	User Authentication: Login functionality, allowing users to access the app with their credentials.
	Password Recovery: Mechanisms to reset forgotten passwords.

2. Time Tracking
	Start/Stop Timer: Users should be able to start and stop a timer to track the time spent on a task or project.
	Continueous stop watch: Users can run the timer for as long as it is required.
	Task/Project Association: The ability to associate time entries with specific tasks or projects.

3. Task and Project Management
	Task Management: Users can create tasks.
	Project Management: Users can create projects with the ability to group tasks under a project.
	Assign Time to Tasks/Projects: Users can link time entries to specific tasks or projects.

4. Reporting and Analytics
	Time Reports: Generate reports that summarize time spent on tasks and projects over a specified period.

5. User Interface and Usability
	Intuitive User Interface: A user-friendly design that is easy to navigate and use.
	Responsive Design: Works well on different devices and screen sizes.
	Accessibility: Compliance with accessibility standards for all users.
----------------------------------------------------------------------------------------------------
NON-FUNCTIONAL REQUIREMENTS:

1. Performance
	The time tracker app is highly responsive, with each user interaction—whether starting or stopping a timer, or generating a report—executed within two seconds or less. 
	It scales effortlessly to accommodate an increasing number of users and data without compromising speed or efficiency.

2. Reliability and Availability
	This app is built with a focus on reliability, ensuring an uptime of at least 99.9%, providing consistent availability to users. 
	Data consistency is kept across the system, even in cases of unexpected interruptions or system failures.

3. Security
	Security is a top priority in theapp. All sensitive data is encrypted both in transit and at rest, protecting user information. 
	The app uses secure Firebase authentication methods to ensure user accounts are protected. Access control is in place, allowing different user profiles with separated data sets.

4. Usability
	The app features an intuitive user interface, designed to be user-friendly and easy to navigate. 
	The design is consistent across all screens, providing a seamless user experience.

5. Maintainability
The app is constructed and documented to facilitate maintenance and future updates. 
	Its modular architecture allows the possibility of adding new features, update existing ones, or fix bugs with ease.
----------------------------------------------------------------------------------------------------
FREQUENTLY ASKED QUESTIONS:

1. How do I create an account on the time tracker app?
	You can create an account by providing basic information like your name, email, and password. Follow the in-app registration process to set up your account.

2. Can I reset my password if I forget it?
	Yes, you can reset your password by clicking the "Forgot Password" link on the login screen. You'll receive instructions via email to reset your password.

3. How do I create and manage tasks or projects?
	You can create tasks or projects by navigating to the relevant section in the app and entering the required information. The app usually allows you to update tasks and projects as needed.

4. How do I generate reports on my tracked time?
	The time tracker app offers a analytics section where you can generate reports based on your time tracking data. You can customize reports by selecting specific time periods.

5. What if the app crashes or doesn't work correctly?
	If the app crashes or has issues, try restarting it or reinstalling it. If the problem persists, check for updates or contact the email listed under "AUTHOR" for support for assistance.
----------------------------------------------------------------------------------------------------
REFERENCES:

Altexsoft (2023). Functional and Non-functional Requirements: Specification an. [online] AltexSoft. Available at: https://www.altexsoft.com/blog/functional-and-non-functional-requirements-specification-and-types/.

‌Varsity College. (n.d.). Open Source Coding (Introduction) Module Manual [PM1]. [online] Available at: 
https://advtechonline.sharepoint.com/sites/TertiaryStudents/IIE%20Student%20Materials/Forms/Default%20View.aspx?id=%2Fsites%2FTertiaryStudents%2FIIE%20Student%20Materials%2FNew%20Student%20Materials%20CAT%2FOPSC7311%2F2024%2FOPSC7311_MO%2Epdf&viewid=db15e059-4f93-487f-abda-e538b821c7b8&parent=%2Fsites%2FTertiaryStudents%2FIIE%20Student%20Materials%2FNew%20Student%20Materials%20CAT%2FOPSC7311%2F2024 [Accessed 2018].

‌

