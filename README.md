<h1>Forensic Investigation</h1>

<h2>Description</h2>

<p>In today’s digital world, most fraud can be tracked electronically. In this task, you will use Basis Technology’s Autopsy application to analyze a storage device for evidence related to a possible violation of company policy. I have analyzed the storage device for data files, deleted data files, directories, or drive partitions. I have also provided screenshots of my evidence, and written a final report.</p>

<h2>Scenario</h2>

<p>An oil company’s senior management has reason to suspect that John Smith, one of the company’s mechanical engineers, allegedly took information that was clearly identified as proprietary. The company’s legal office has requested digital evidence regarding the potential violation of company policy, which prohibits the sharing of proprietary information without prior approval. The employee was not authorized to access proprietary information. All employees sign nondisclosure agreements (NDAs) and acceptable use policies (AUPs). Senior management and the legal office have approved the request for digital evidence.

I am a member of the investigative team that has been assigned to examine the digital evidence captured from the suspect’s office laptop computer. I have created an incident report to present the findings to senior management.</p>

<h2>Steps Taken to Create the Forensic System Case File</h2>

<p>To begin the investigation, we systematically set up a new case in Autopsy to ensure a structured analysis:</p>

- Opened the **Autopsy** application.
  <p align="center">
  <img src="https://i.imgur.com/Yb70xqt.png" height="80%" width="80%" alt="Autopsy"/>
- Selected **New Case** from the main interface. Entered the case name **John Smith Investigations**. Selected Browse in Base Directory then chose **C:\Users\LabUser\Desktop\Evidence Files**. Clicked **Next**.
  <p align="center">
  <img src="https://i.imgur.com/H68khZm.png" height="80%" width="80%" alt="Autopsy"/>
  <img src="https://i.imgur.com/vA7eQYZ.png" height="80%" width="80%" alt="Autopsy"/>
- Specified the **case number and examiner's name**, then clicked **Finish**.
  <p align="center">
  <img src="https://i.imgur.com/ZVN96XJ.png" height="80%" width="80%" alt="Autopsy"/>

<h2>Steps Taken to Identify Potential Evidence</h2>

<p>With the case file set up, we proceeded to identify potential evidence related to the suspected policy violation:</p>

- Clicked on **Generate new host name based on data source name**, then **Next**.
  <p align="center">
  <img src="https://i.imgur.com/vQ2fG3m.png" height="80%" width="80%" alt="Autopsy"/>
- Clicked on **Disk Image or Image File**, then **Next**.
  <p align="center">
  <img src="https://i.imgur.com/8YO21AS.png" height="80%" width="80%" alt="Autopsy"/>
- Selected **Data Source path**, browsed to: **C:\Users\LabUser\Desktop\Evidence Files\JSmith_Q1.001**, then click **Open**. Accept defaults, **Next**.
  <p align="center">
  <img src="https://i.imgur.com/ZKcACVL.png" height="80%" width="80%" alt="Autopsy"/>
  <img src="https://i.imgur.com/5RBCDJP.png" height="80%" width="80%" alt="Autopsy"/>
- **Configured Ingest**, accept defaults, **Next**.
  <p align="center">
  <img src="https://i.imgur.com/uIxQC1b.png" height="80%" width="80%" alt="Autopsy"/>
- **Add Data Source**, waited for the message **“Data source has been added to the local database. Files are being analyzed”**, clicked on **Finish**.
  <p align="center">
  <img src="https://i.imgur.com/49dauCP.png" height="80%" width="80%" alt="Autopsy"/>

<h2>Findings and Conclusions</h2>

<p>The investigation yielded significant findings that suggest a violation of company policy:</p>

- **Unauthorized Access to Proprietary Files:** Discovered several proprietary documents in John Smith's user directories that he was not authorized to access. The files included Drilling Methodology, Business Strategy, and Oil Company Data Strategy.
  <p align="center">
  <img src="https://i.imgur.com/TV5HKSd.png" height="80%" width="80%" alt="Autopsy"/>
  <img src="https://i.imgur.com/1UHsON4.png" height="80%" width="80%" alt="Autopsy"/>
  <img src="https://i.imgur.com/f01qyXe.png" height="80%" width="80%" alt="Autopsy"/>
- **Deleted Files Recovery:** Recovered deleted files where John Smith was accessing propriety files like the Business_Strategy.pdf and Drilling Methodology.pdf as shown below.
  <p align="center">
  <img src="https://i.imgur.com/CSmrtBW.png" height="80%" width="80%" alt="Autopsy"/>
- **Conclusion:** Based on the collected evidence, it is concluded that John Smith accessed proprietary information without authorization, violating the company's nondisclosure agreement and acceptable use policies.
