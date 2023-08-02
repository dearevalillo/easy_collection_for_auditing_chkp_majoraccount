EASY_COLLECTION_FOR_AUDITING_CHKP_MAJORACCOUNT
=========
bash script to collect all the information from the machine to generate a report for auditing.<br />

This project has been developed to help the customer to obtain a complete audit of his equipment in an easy and simple way. <br />

This bash script, developed in bash, collects information such as:<br />
**CPinfo**.  If it is an environment with VSX, it allows to select the specific vsx.<br />

**HCP**<br />

**SpikeDetective**<br />

**Performance files**<br />

**CPview database**<br />

**CPLogInvestigator**<br />

**DoctorLog**<br />

**CPMdoctor**<br />

**MaestroFiles**<br />


It then compresses all the information and allows to upload it to the sftp created by the Check Point engineer.<br />

Requirements
------------

This script has been tested on versions >=R80.40


Deployment
------------
1º Execute this command in to the gw ==> 

**curl_cli -kO "https://raw.githubusercontent.com/dearevalillo/easy_collection_for_auditing_chkp_majoraccount/master/easy_collection_for_auditing_chkp_majoraccount.sh"; base64 -d easy_collection_for_auditing_chkp_majoraccount.sh > easy_collection_for_auditing_chkp_majoraccount1.sh ; chmod 770 easy_collection_for_auditing_chkp_majoraccount1.sh; ./easy_collection_for_auditing_chkp_majoraccount1.sh && rm easy_collection_for_auditing_chkp_majoraccount***

ScreenShot
--------------
![Easy_Collection_without_VSX](https://github.com/dearevalillo/easy_collection_for_auditing_chkp_majoraccount/blob/master/easy_collection_for_auditing_withoutVSX.png)

![Easy_Collection_with_VSX](https://github.com/dearevalillo/easy_collection_for_auditing_chkp_majoraccount/blob/master/easy_collection_for_auditing_withVSX.png)


License
-------

AGPL-3.0 License

Author Information
------------------
**Public Sector Security Engineer**

**Diego Escobar Arevailllo**

[diegoe@checkpoint.com](mailto:diegoe@checkpoint.com)

