# 360 Courier


## Command Line Interface

360 Courier accepts a single command line argument, this argument consists of semi-colon separated key value pairs.

```cmd
"<CourierFullPath>" "patfirstname=Jennifer;patlastname=Brown;patsex=female;dpsprojectfilepath=D:\cases\35741 - brown, jennifer.dps;"
```

### Courier Full Path value <CourierFullPath>
  * We can get courier full path from registry under this registry path **"HKEY_CURRENT_USER\Software\360 Imaging\360 Courier"** under Key name: **"AppPath"**

### Arguments

* **patfirstname:** Patient first name (mandatory)
* **patlastname:** Patient last name (mandatory)
* **dpsprojectfilepath:** File path single file (mandatory) 
* **patsex:** Patient's gender (expected values: m, male, f or female) (optional)
* **patbirthdate:** Patient's date of birth (yyyyMMdd) (optional)
* **guidetype:** Guide Type  (optional)
* **implanttype:** Implant Type  (optional)
* **implantupperarch:** Teeth to be restored in the upper arch (v0.15+), Using universal numbering
* **implantlowerarch:** Teeth to be restored in the lower arch (v0.15+), Using universal numbering

### Example:

```cmd
"C:\Users\administrator\AppData\Roaming\360 Courier\360 Courier.exe" "patfirstname=Jennifer;patlastname=Brown;patsex=female; patbirthdate=19800615;dpsprojectfilepath=D:\cases\35741 - brown, jennifer.xml;"
```

### Supported  implant types ###
* Adin Implants
* American Dental
* Bicon
* Biohorizons
* Biodenta
* Biomet 3I
* Camlog
* Dentium
* Dentsply
* Glidewell
* Hiossen
* Implant Direct
* INTRA-LOCK
* JDental Care
* Keystone
* MIS
* Megagen
* Neoss
* Neodent
* NeoBiotech
* Nobel Biocare
* OCO Biomedical
* Paltop
* Ritter Implants
* Straumann
* Sweden & Martina
* Southern Implants
* Thommen
* TRATE AG
* Z-Systems
* Zest Anchors
* Zimmer
* Other

### Guide Type ###
* Pilot Guide
* Multi Guide
* Depth Control
