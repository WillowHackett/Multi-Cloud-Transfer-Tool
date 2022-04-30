# Multi Cloud Transfer (Advanced!) 🔥
<p><b>1.Setup and Start using Rclone on Google Colab and Create/Edit/View and delete your Rclone config file and keep them always with you using this! No matters which device you are on! Use Anywhere and Anytime and perform all Rclone task and immediately save it!</b></p>
<p><b>2.Now I have implemented the Multi Cloud Transfer tool! it means you can easily transfer your all account data to any Cloud service which you like! And since it will work on Google Server, So it will be lightning fast⚡and will not consume your Internet or System Resources.😉</p></b>
<h2><b>🆕What's New!🆕</b></h2>
<p><b><i>v2.2.7 (Service Accounts support and warning time.)</i></b></p>
<h4><b>1.Added Service Accounts support.🪀</b></h4>
<h4><b>2.Warning time added in Delete section to prevent accidental data loss.⚠️</b></h4>
<h4><b>3.More Purge options are added!🧼</b></h4>
<h4><b>4.New Transfer Modes are added!🔮</b></h4>
<h4><b>5.Now use Different Rclone Flavours!😋</b></h4>
<p><b><i>v2.2.6 (More Transfer Methods and Purge options!)</i></b></p>
<h4><b>1.Added more Transfer modes as rclone.🚅</b></h4>
<h4><b>2.Now delete or purge your data.🗑️</b></h4>
<h4><b>3.Fixed duplicates rclone.conf Errors.</b></h4>
<p><b><i>v2.2.5 (Multi Cloud Transfer Integration)</i><b></p>
<h4><b>1.Multi Cloud Transfer Tool Added!⚡</b></h4>
<h4><b>2.Auto Reconnecter is Added in support of large transfer.😙</b></h4>
<h4><b>3.Added New Sections and updated the guide.😌</b></h4>
<h4><b><i>4.Service Accounts Randomizer (In Beta)</i></b></h4>
<h4><b>5.Config will now move to My Drive at place of frustrating you by downloading in your Device.</b></h4>
<p><b><i>v2.2.4 (R-1.58.0)</i><b></p>
<h4><b>1.Project upgraded & optimized for Rclone 1.58.0 🙃</b></h4>
<h4><b>2.Multi Cloud Transfer Tool (in Beta)</b></h4>
<h4><b>3.Guide Updated and Steps are added for new auto-config authorization.</b></h4>
<p><b><i>v2.2.3 (Migrating to 1.58.O Beta)</i></b></p>
<h4><b>1.Rclone will now auto-fetch the saved progress including Rclone config file (If Any) from your Google Drive (My Drive).🔥</b></h4>
<h4><b>2.Now you can use your own Rclone Config File! Just upload it to your My Drive and fetch it</b>🙃</h4>
<h4><b>3.File will be shifted to Google Drive at place of starting download to your Device!</b></h4>
<p><b><i>v2.2.1 (R-1.57.0)</i></b></p>
<h4><b>1.Create/Delete/Edit Rclone config file/remote!🤩</b></h4>
<h4><b>2.Download Rclone config file!😀</b></h4>
<h4><b>3.Support all Rclone Commands!😎</b></h4>
<h4><b>4.Store your Rclone progress on Cloud and access it from anywhere!😉</b></h4>
<h2><b>⛔ NOTICE</b></h2>
<h4><b>1.The Project is now updated and everything is optimized for new changes made by Rclone v1.58.0 written in 2nd point.</b></h4>
<h4><b>2.In Latest Rclone Version v1.58.0, they made some changes in Auto-Config. Don't worry I am aware of that and till that you can either follow the New Steps or if you are making config file for Google Drive then you can provide your CLIENT ID and CLIENT SECRET to Work around that situation! I will update you in my Update Channel ,once I find some alternative to help you out in that Step.</b></h4>
<h4><b>3.For auto-config always choose No(n) because we are going to run the Rclone not on our own local device! Otherwise login will not work.</b></h4>
<h2><b>📝 Introduction</b></h2>
<h4><b>This Project makes it easy and possible to Perform every Rclone Task on Google Colaborately and Store your progress on the cloud and continue it where you left it anytime and anywhere! This Project comes with In-Build support to perform basic task like Creating/Editing/Viewing and Deleteing and also Downloading your Rclone Config file which is needed by almost all Rclone User to perform task! To execute any rclone command you just need to type "!rclone" (After installing Required Setup Files) before any command like "!rclone config" where config is the Command name!</b></h4>
<!--- Step Area Begin --->
<h2><b>🔌Before you Start!</b></h2>
<h4><b>Please Connect your Google Account, So that Rclone can easily save its progress automatically.</b></h4>
<img src="Img/rq-1.png">
<h4><b>If you want to use your own Rclone config file or the progress saved in your Google Drive in My Drive! Then run the following Code as shown in the image</b></h4>
<img src="Img/rq-2.png">
<h4><b>Run the Time Out Preventer to prevent Google Colab from getting timeout before your Transfer got Completed.</b></h4>
<img src="Img/30.png">
<h2><b>⚙️ How to use?</b></h2>
<h4><b>1.First Open the Code on Google Colab: <a href="https://colab.research.google.com/github/TheCaduceus/Rclone-Setup-on-Google-Colab/blob/main/Rclone.ipynb" alt="Open Code">Open Code</a></b></h4>
<h4><b>2.Now,Before performing anything Run the Code as shown in the Image to download Setup and configure Rclone!</b></h4>
<img src="Img/1.png" alt="1">
<h4><b>3.To Create/Edit/Delete/View comfig file/remote just run the code as shown in the Image.</b></h4>
<img src="Img/2.png" alt="2">
<h4><b>4.After Running the Code! Checkout the available options (shown in image) and choose a type alphabet and hit Enter key to continue, but if input filed is not visible then just click on the blinking line.</b></h4>
<img src="Img/3.png" alt="3">
<h4><b>5.Type n and hit Enter to create a new Config file or Remote and give name, So that you can identify it in future</b></h4>
<img src="Img/4.png" alt="4">
<h4><b>6.Now after Entering the name! You have to choose the cloud for which you have to make config file or remote (by typing its list number), like if you need to make config file or remote of Google Drive then type number "16" and hit Enter</b></h4>
<img src="Img/5.png" alt="5">
<h4><b>7.If you don't know about Client ID and Client Secret then just hit Enter without entering anything! Otherwise this can be used to bypass login into your Google Account</b></h4>
<img src="Img/6.png" alt="6">
<h4><b>8.After that, It will ask you to grant which level of access to your Rclone config file, to choose it just type and hit enter the list number! I recommend to use number '1' which is for full access.</b></h4>
<img src="Img/7.png" alt="7">
<h4><b>9.If you want to use "Computers" folder than you can provide its root_folder_id otherwise just hit Enter to ignore</b></h4>
<img src="Img/8.png" alt="8">
<h4><b>10.Again! If you want to use Service Accounts then you can fill the shown field otherwise leave it and hit Enter!</b></h4>
<img src="Img/9.png" alt="9">
<h4><b>11.Also, for doing advanced configuration you can type y or just hit Enter to ignore it.</b></h4>
<img src="Img/10.png" alt="10">
<h4><b>12.This is a important step! For Auto-Config write 'n' and hit Enter because here we are using a Remote Machine which is not our Device! So always choose 'n' otherwise login will not work.
<img src="Img/11.png" alt="11">
<h4><b>13.Now Rclone will ask you to type something like "rclone authorize "drive" "XXXXXXXXXXX" in your own Computer or Mobile Phone! Please read the following steps carefully!<b></h4>
<img src="Img/23.png">
<h3><b>For 📲Mobile Phones:</b></h3>
<h4><b>1.First Download Termux App in your Phone: <a href="https://play.google.com/store/apps/details?id=com.termux">Android</a> | <a href="https://apps.apple.com/us/app/xterminal-ssh-terminal-shell/id1544728400">iOS</a></b></h4>
<h4><b>2.Now Run the Following Commands one by one in it!</b></h4>
<p><b>
  1.pkg install rclone<br>
  2.Command given by Rclone in STEP 13!<br>
  </b></p>
<h4><b>3.After it! Rclone will open Browser for login into your Account!</b></h4>
<img src="Img/19.jpg">
<h4><b>4.Once you Successfully login! Return back to Termux App and copy the code which will apper there and paste it into the Google Colab to continue!</b></h4>
<h3><b>For 🖥️PC:</b></h3>
<h4><b>1.Download Rclone, as per the Operating-System in your PC: <a href="https://rclone.org/downloads/">Download Now</a></b></h4>
<h3><b>For Windows:</b></h3>
<h4><b>2.After Downloading Rclone zip for Windows! Extract it and open the Folder as shown in the Image.</b></h4>
<img src="Img/20.png">
<h4><b>3.Now type CMD in the Address bar and hit Enter to configure CMD in that folder and to use Rclone.</b></h4>
<img src="Img/21.png">
<h4><b>4.It will open CMD, Now Enter the command given by Rclone in the STEP 13 written above. It will open the Browser, so just login into your account return back to CMD Window</b></h4>
<img src="Img/22.png">
<h4><b>5.Once you login successfully! A Code will be visible. Just copy the code and paste it in Google Colab to continue.</b></h4>
<h3><b><i>For Linux:</i></b></h3>
<p><b>Read Here: <a href="https://www.addictivetips.com/ubuntu-linux-tips/set-up-rclone-for-linux/">Rclone on Linux</a></b></p>
<h3><b><i>For MacOS:</i></b></h3>
<p><b>Read Here: <a href="https://roadtopetabyte.medium.com/tutorial-how-to-install-rclone-and-configure-rclone-browser-on-your-mac-rclone-gui-for-macos-a97e13925ab0">Rclone on MacOS</a></b></p>
<h4><b>14.Now, it will ask you if you want to use Shared Drive or not ? y for Yes and n for No.</b></h4>
<h4><b>15.If you want to use Shared Drive then it will ask you to choose the list number of Shared Drive from the list shown (of available Shared Drive in your Account.)</b></h4>
<img src="Img/14.png" alt="14">
<h4><b>16.Finally! After above steps, it will show you the final code of rclone config file, you can copy paste it in any Text Editor and after that type 'y' and hit Enter to confirm and then type 'q' tp quite the configuration of file.</b></h4>
<img src="Img/15.png" alt="15">
<img src="Img/16.png" alt="16">
<h4><b>17.After Typing q and hitting Enter! The program will automatically save the rclone.conf file in your My Drive.</b></h4>
<img src="Img/17.png" alt="17">
<h4><b>18.You can execute or run any Rclone command in this project! Just click on the Drop-down arrow of "Advanced Task" and that sit! Enjoy</b></h4>
<img src="Img/18.png" alt="18">
<!--- Step Area Ended --->
<h2><b>📑Creating Config File for More Clouds</b></h2>
<p><b>You can learn creating config file for all Cloud Services: <a href="https://rclone.org/docs/">Learn Here</a></b></p>
<h2><b>🪝Multi Cloud Transfer</b></h2>
<p><b>Lets move Data from any cloud to any cloud as you want! Since we are using Colab, So it will not consume your Internet or System Resource.</b></p>
<h4><b>1.Before we procced! I recommend to either create or fetch your Rclone Config file to Google Colab using above two methods! Creating and fetching will automatically place the file in correct location!</b></h4>
<img src="Img/24.png">
<h4><b>2.Once you done creating or fetching the config file! Just run the Code named "Connect to Cloud Accounts" and it will automatically detect your config file and will show you  dropdown list to mount multiple remotes as shown in the image. Now select remoted and click mount to connect to those remotes between which you have to transfer your Data.</b></h4>
<img src="Img/25.png">
<h4><b>3.After mounting those remotes or Cloud Accounts, Now click on the File icon as shown in the image and then you will see two folder named "drives" open the second folder named "drives" and you will see the names of Remotes or Cloud Account which you mounted previously!</b></h4>
<img src="Img/26.png">
<h4><b>4.Now Simply open that Folder and copy the file or folder path which needs to be copied and then right click on the file or folder and select "Copy Path" option from the list</b></h4>
<img src="Img/27.png">
<h4><b>5.After that! Paste the path of file or folder in "Source" field and again go to File Icon-->drives and open the Cloud Account into which you want to transfer files/folders and copy its path! You can either directly copy the path of Cloud Account or of any folder inside it and paste the path in "destination" field.</b></h4>
<img src="Img/28.png">
<h4><b>6.Choose the Transfer mode trough which you want to transfer your Data! Please refer to "<a href="#modes-of-transfer">🚅Modes of Transfer</a>" below to learn about all of them.</b></h4>
<h4><b>7.If you want to get notified! when your transfer got completed then tick the Email_notification option and provide Gmail Email ID as well as its password and the Receiver Email ID on which you want to receive the notification!  (optional)</b></h4>
<p><b>
  Email_notification: Select this option to enable following options.<br>
  logs: Check this option to also get log in Mail.<br>
  emailID: Enter your Gmail ID.<br>
  password: Enter Password of given Gmail ID.<br>
  Receiver_ID: The Email ID on which you want to receive the Notification.
  </p></b>
<img src="Img/29.png">
<h4><b>8.Dry Run option is just to check the Source as well as destination path without copying anything.(Optional)</b></h4>
<h4><b>9.Finally! Run the code by pressing Play button to start transferring. Enjoy!🙃</b></h4>
<h2><b>🪀Using Service Accounts</b></h4>
<h4><b>The service accounts can be used to bypass the 750Gb/day upload limit set by google in Google Drive. It means that you can use them to upload more than 750Gb per day, duplicate hundreds of files...Each service account has a 750Gb upload limit per day. You can create up to 100 service account per google cloud project. So, with only one project you can upload/duplicate up to 75Tb a day!</b></h4>
  <h4><b>1.Don't have Service Accounts?<a href="https://telegra.ph/How-to-create-and-use-service-accounts-sa-03-31" alt="Creating SA"> Create Here</a></b></h4>
  <h4><b>2.After creating! make the zip of "accounts" folder which have 100 Json files and keep its name as "accounts.zip".</b></h4>
  <h4><b>3.Now back to Google Colab screen and run the code as shown in the Image and click "Choose file" and select the zip file you just created!</b></h4>
  <img src="Img/31.png">
  <h4><b>4.After it! Click the file icon, then open "accounts" folder and right click on anyone json file and select "Copy path".</b></h4>
  <img src="Img/32.png">
  <h4><b>5.Run the "Create/Edit/Delete Rclone Config File" and paste the path in "service_account_file" during createing remote for Google Drive.</b></h4>
  <img src="Img/33.png">
<h2><b>🚅Modes of Transfer</b></h2>
<h4><b>As this project use Rclone as a base! and Rclone support multiple flags to help you move or clean your Data, in this Project flags are known as Modes. Here is the list of the Modes that this Project supports:</b></h4>
  <h4><b>1.Copy: Copy files from source to dest, skipping identical files.</b></h4>
  <h4><b>2.Copyto: This can be used to upload single files to other than their current name.</b></h4>
  <h4><b>3.CopyURL: Download a URL's content and copy it to the destination without saving it in temporary storage.</b></h4>
  <h4><b>4.Move: Moves the contents of the source directory to the destination directory.</b></h4>
  <h4><b>5.Moveto: If source:path is a file or directory then it moves it to a file or directory named dest:path.</b></h4>
  <h4><b>6.Check: Checks the files in the source and destination match. It compares sizes and hashes (MD5 or SHA1) and logs a report of files that don't match. It doesn't alter the source or destination.</b></h4>
  <h4><b>7.Sync: Sync the source to the destination, changing the destination only. Doesn't transfer files that are identical on source and destination, testing by size and modification time or MD5SUM. Destination is updated to match source, including deleting files if necessary (except duplicate objects, see below).</b></h4>
  <h4><b>8.Bisync: Bisync provides a bidirectional cloud sync solution in rclone. It retains the Path1 and Path2 filesystem listings from the prior run. On each successive run it will:</b></h4>
  <h4><b>9.Cat: Rclone cat sends any files to standard output.</b></h4>
  <h4><b>10.CleanUp: Clean up the remote if possible. Empty the trash or delete old file versions. Not supported by all remotes.</b></h4>
  <h4><b>11.ls: List all the objects in the path with size and path.</b></h4>
  <h4><b>12.lsd: List all directories/containers/buckets in the path.</b></h4>
  <h4><b>13.lsl: List all the objects in the path with size, modification time and path.</b></h4>
  <h4><b>14.md5sum: Produce an md5sum file for all the objects in the path.</b></h4>
  <h4><b>15.sha1sum: Produce a sha1sum file for all the objects in the path.</b></h4>
  <h4><b>16.size: Return the total size and number of objects in path.</b></h4>
  <h4><b>17.genautocomplete: Output shell completion scripts for rclone.</b></h4>
  <h4><b>18.gendocs: Output markdown docs for rclone to the directory supplied.</b></h4>
  <h4><b>19.obscure: Obscure password for use in the rclone.conf.</b></h4>
  <p><b>Following Modes can easily cause Data Loss:</b></p>
  <h4><b>1.Delete: Remove the files in path.</b></h4>
  <h4><b>2.Purge: Will delete whole Directory and leaving nothing behind.</b></h4>
  <h4><b>3.rmdir: Completely Delete the given path.</b></h4>
  <h4><b>4.rmdirs: Remove any empty directories under the path.</b></h4>
<h2><b>🎯Points to be Remembered</b></h2>
<h4><b>1.Always choose No (n) for Auto-Config because we are not going to use Rclone on our Local Device/Machine otherwise login will not work!</b></h4>
<h4><b>2.Don't forget to type '!' before executing any custom Rclone Command.</b></h4>
<h4><b>3.For Safety! Rclone will always save progress in your My Drive! Not in any of your Shared Drive.</b></h4>
<h4><b>4.Use the Dry Run option to check both Source and Destination path without copying anything.</b></h4>
<h4><b>5.You can either choose the path of Cloud Account folder or anyother folder inside it</b></h4>
<h2><b>Supported Command List</b></h2>
<h4><b><a href="https://github.com/TheCaduceus/Rclone-Setup-on-Google-Colab/blob/main/Cmds.md">Show List</a></b></h4>
<h2><b>🤔Why use this?</b></h4>
<h4><b>1.Rclone is really a very powerful command line tool! but some users are really not comfortable with Command line and hence it become defficult to use this type of useful tools, So this Project provides a very interactive User Interface (UI) to operate it with less inputs.</b></h4>
<h4><b>2.Rclone creates "rclone.conf"  file, which is the most important thing to make rclone useful. But when you change your device, then you have to create a new rclone.conf file. But this Project saves your rclone.conf file to Google Drive and you can use the same file repeatedly, what you just need is your Google Account and nothing.</b></h4>
<h4><b>3.Heavy flexibility: You can use this project anytime & anywhere because it is totally cloud based, that means if you are moving files in your PC and want to check its progress in your phone then you just have to login on Google Colab in your Phone.</b></h4>
<h2><b>🔐 Safe or Not? ✅</b></h2>
<h4><b> 1.Don't Worry! No data will be shared with anyone, if you use the <a href="https://github.com/TheCaduceus/Multi-Cloud-Transfer-Tool">Original code</a>.🔒</b></h4>
<h4><b> 2.This code do not share even a single piece of data to any third party source and not create any log of that!🔑</b></h4>
<h4><b> 3.Do not trust any other copy of this Code.📚</b></h4>
<h2><b>⛑Contact Us!</b></h2>
<h4><b>Join our Update Channel at Telegram:<a href="https://telegram.me/TheCaduceusUPDATE"> Join Now!</a></b></h4>
<h4><b>Directly Contact the Developer using Telegram <a href="https://telegram.me/HelpAutomatted_Bot">@HelpAutomatted_Bot</a></b></h4>
<h2><b>❤️Credits & Thanks</b></h2>
<p><b><a href="https://github.com/TheCaduceus">Dr.Caduceus</a>: For making this Project and Guide.</b></p>
<p><b><a href="https://rclone.org/">Rclone</a>: The Backbone of this Powerful Project.</b></p>
