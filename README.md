# PCLinuxOS Medical Live CD

Welcome to PCLinuxOS Medical livecd!  

This ISO is based on PCLinuxOS Gnome Zen Mini with [openEMR](https://www.open-emr.org/) v 4.1.0 installed.  

## Installed software

**Medical**  
* [openEMR v4.1.0](https://www.open-emr.org/)

**Tools to install openEMR**  
* mysql-administrator  
* mysql-gui-tools  

**Backup**  
* deja dup  
* gnomebaker  

**Graphics**  
* gimp  
* inkscape  

**Remote management**  
* teamviewer
  
**Video**  
* vlc  
  
**pdf tools**  
* evince  
* pdfedit  


## Test the ISO

To test LiveCD, run Firefox or Chromium. It will open a DEMO environment (you need Internet). 
There's a DEMO that the patient can see his visits.

** USER-PASS** for DEMO are:

> Administrator: **admin - pass**  
> Physician (more permissions than clinician): **physician - physician**  
> Clinician (less permissions than physician): **clinician - clinician**  
> Accountant: **accountant - accountant**  
> Information desk: **receptionist - receptionist**  

Pass for patients DEMO:

> Susan1 - susan  
> Phil2 - phil

Because of *permissions* of LiveCD, you must install LiveCD to use openEMR.
PASSWORDS for installed openEMR are:

> Administrator: **admin - admin**  
> User: **medical - medical**  

## Install PCLinuxOS Medical
If you want to install PCLinuxOS Medical: 

**PCLOS Menu Button -> More Apllications -> Configuration -> Install PCLinuxOS Medical**  
  
follow the installation instructions.

USER-PASS are:

> Root: **root - root**  
> User: **medical - medical**  
  
After the installation you'll have a user *medical*.

## Screens

![PCLinuxOS GNOME ZEN](/images/pclinuxos_gnome_zen.png)

![openEMR Login](/images/openemr_login.png)

![openEMR Patient](/images/openemr_search_patient.png)

![Patient Login](/images/openemr_patient_login.png)

![Patient Portal](/images/openemr_patient_portal.png)

## DISCLAIMER

Logos and trade names of openEMR and PCLinuxOS, do not belong to me.
