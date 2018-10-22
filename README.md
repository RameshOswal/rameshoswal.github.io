# Currently Publishing at http://www.andrew.cmu.edu/user/ramesho/
# To publish the website follow steps on :
	## Create a www Directory
		The university provides every Carnegie Mellon affiliate with space on the Andrew File Server (AFS) for a personal website. In addition, each faculty member and teaching assistant can request a Project Volume on the AFS, where they can store course website files in a www directory.

		Follow these steps to create a www directory in your personal or course AFS space.

		Open a supported Telnet client; Tectia (Windows), Terminal (Mac) and connect to the UserWeb and Course Web server. 
		Host: unix.andrew.cmu.edu
		Userid or User Name: your Andrew userID
		Password: your Andrew password
		CourseWeb files only - type the following UNIX command to change your working directory to the course Project Volume
		cd pathname
		where pathname is the path you were given when you requested your Project Volume
		At the prompt, type the following UNIX command to create the www directory where you will store your website files:
		mkdir www

		Note: If you see the message mkdir: cannot create directory 'www': File exists, your www directory has already been created.
		To set access rights, which give the server read access to your www directory, type the following UNIX command.
		fs sa www system:anyuser rl 
	 ## Transfer Files
		After you develop your website, you can transfer the files to the www directory you created on the andrew.cmu.edu host server. Use a supported Secure File Transfer Protocol (SFTP) client to transfer files; SSH Tectia Client (Windows) or Fetch (Mac).

		IMPORTANT: Name the first page in your www directory index.html (all lowercase). Consider the index page to be the landing page of the folder.

		Launch the SFTP client. You will be prompted to login if you have not already done so through an active browser session.
		Use the following settings to connect to the UserWeb and Course Web server. 
		Hostname: unix.andrew.cmu.edu
		Userid: your Andrew userID
		Password: your Andrew password
		Directory: ~/www
		For course pages, navigate to your course's directory at the path:
		/afs/andrew.cmu.edu/course/courseid/www
		 where courseid is the course ID number and www is the location of the www directory of your Project Volume.
		Transfer (copy) all your website files to the www directory.
		Note: Refer to the documentation for your SFTP program for more information about transferring files. If you are using an Andrew workstation, you can use the UNIX command cp to copy the files. For additional help with using this command, enter "man cp" in UNIX.
	 ## Publish Files
		Follow these steps to publish your website.

		In your web browser, visit Publishing on www.andrew.

		Note: Use UserWeb and CourseWeb KWPublish for authenticated (password-protected) publication. Use authenticated publication only for collections that have a configured .kwpublish file to restrict publication rights by IP address or Andrew UserID.
		Select the appropriate radio button for Personal or Course web pages.
		Enter your Andrew UserID or course number, then click Publish.
		Note: If a section letter or other text is part of the course number you submitted in your request for a project volume, you must include it in the course number.
 http://www.cmu.edu/computing/services/comm-collab/websites/user-course-web/how-to/publish.html#publish 


 # TODO
 	## Write about auto-trader project, Portfolio management using Reinforcement Learning