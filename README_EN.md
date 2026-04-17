# Install-Nessus-on-Kali

<h2>A walkthrough on how to install Nessus on Kali</h2>

<h3>What is Nessus?</h3>

<b>Nessus</b> is a <b>vulnerability assessment</b> tool developed by <b>Tenable, Inc.</b>
Nessus scans network, servers, applications and other systems for potential weaknesses that could be exploited by attackers.


<h2>Download Nessus</h2>
On your kali, use the web browser (firefox) to download Nessus using this <a href="https://www.tenable.com/downloads/nessus"=blank>link.</a>
Select the appropriate linux distribution (Debian/Kali) as shown in the image below.


<img src="Pictures/Pic 1.jpg">

Navigate to the folder where the <strong><i>.deb file</i></strong> is located and right click inside where the file is and <b>open terminal here</b> as shown in the image below.


<img src="Pictures/Pic 2.jpg">


Once you are on the terminal, run the command <b><i>sudo dpkg -i "filename".deb</i></b> or <b><i>sudo apt install ./"filename".deb</i></b> to install Nessus. (Replace filename with the name of the nessus file).
<p>After installing, start the nessus service by running command <b><i>systemctl start nessusd</i></b>.</p>
<p>Confirm if the nessus service is active by running command <b><i>systemctl status nessusd</i></b>.</p>
<p>Once it is active, go to the web browser in kali (firefox) and type <b><i>https://kali:8834</i></b> or directly click on the link that will be at the bottom after running the <b>start command</b> as shown below.</p>


<img src="Pictures/Pic 3.jpg">


