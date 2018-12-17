# Convert-NAVTxtObjectsToAL
[Convert-NAVTxtObjectsToAL](https://github.com/ederlealsilva/Convert-NAVTxtObjectsToAL) uses a powershell script to help you convert Microsoft Dynamics NAV Txt Objects To AL Syntax

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
The [Convert-NAVTxtObjectsToAL] allows you with one run doing the following tasks.
```
* Export the objects from a database
* Split all the objects
* Convert the txt objects to AL
* Convert the reports RDLC to RDL
* Create the AL project file structure
```
See Usage for additional help.

---

### Prerequisites
* Powershell >= 2.0
* Microsoft Dynamics NAV >= 2018
* Txt2Al.exe
```
This script uses the NAV binary Txt2Al locatated at RoleTailored folder for NAV2018 or BC130
 - C:\Program Files (x86)\Microsoft Dynamics NAV\110\RoleTailored Client\Txt2Al.exe
 - C:\Program Files (x86)\Microsoft Dynamics 365 Business Central\130\RoleTailored Client\Txt2Al.exe
```

---

### Installation
* Copy the files to your computer
* Edit the file [Execute.ps1]
* Change the variables names and set the full path for [Convert-NAVTxtObjectsToAL.psm1]
* Execute the [Execute.ps1] as Administrator.

---

## Usage
* Copy the files to your computer.
* Change the [Execute.ps1] $variables and set the full path for the module [Convert-NAVTxtObjectsToAL.psm1].
* Run the [Execute.ps1] as admin.

---

## Contribution

Please read [CONTRIBUTING.md](https://github.com/ederlealsilva/Convert-NAVTxtObjectsToAL) for details on our code of conduct, and the process for submitting pull requests to us.

---

## Authors

* [**Éder Leal da Silva**](https://github.com/ederlealsilva)

See also the list of [contributors](https://github.com/ederlealsilva/Convert-NAVTxtObjectsToAL/contributors) who participated in this project.

---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](https://github.com/ederlealsilva/Convert-NAVTxtObjectsToAL/blob/master/LICENSE)**
- Copyright 2018 © <a href="https://github.com/ederlealsilva/" target="_blank">Éder Leal da Silva</a>.
