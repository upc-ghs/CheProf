# CheProf
CheProf (CHEmical PRocesses Object-oriented with Fortran2003) is a platform for hydrogeochemical calculations. The repository contains 4 executables for Windows (64 bits) with examples. 
- CheProfReadWrite: It can read output files of Phreeqc and writes it in xml format for CheProf.
- ChemMix: It calculates the chemistry when two end members are mixed.
- ReTra1D: It calculates reactive transport in a 1D domain with uniform flow, using the Direct Substitution Apporach.
- WMA1D: It calculates reactive transport in a 1D domain with uniform flow, using the Water Mixing Apporach.

For additional details about the input files we refer to the [Documentation](Documentation.pdf).

By downloading CheProf.zip and extracting the files the executables can be used directly. Each executable (CheProfReadWrite, ChemMix, ReTra1D, WMA1D) has a folder with one or more examples. Each example contains XML input file and a batch file "run.bat". Double clicking on "run.bat" executes the executable.

The xml input files can best be viewed and edited by means of Notepad++, which is most probably already installed on your computer. If not, it can be downloaded from https://notepad-plus-plus.org/.
To take advantage of the XML language, it is recommended to install the plugin "XML Tools" in Notepad++. To do so start Notepad++ and navigate to "Plugins" ->"Plugins Amin...", search "XML Tools" in the list of all the available plugins. Select the checkbox. Click the "Install" button to complete the installation of XML Tools.
XML Tools can be used to check the XML language, that is, to check whether the file is written in a correct XML format. To do so, click "Plugins" -> "XML Tools" -> "Check XML syntax now".
XML Tools can be used also to validate the file, that is, to check whether the file is written according to the CheProf input file description explained in the documentation. To do so, click "Plugins" -> "XML Tools" -> "Check XML syntax now". It asks to "Please select XML schema (XSD)". Click on the "..." to search for a XML schema. You must select the file "CheProf.xsd" in the "CheProf" folder.

