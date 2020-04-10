IniFlu Readme

Minimum system requirements
  Microsoft Windows XP (64-bit) or later operating system
  Microsoft Office 2016 or later (Excel 64-bit)
  Java 6 or later

Recommended system requirements
  Microsoft Windows 10 1903
  Microsoft Office  365 or Office 2019 (Excel 64-bit)
  Java 10 (64-bit)

Installation
  Copy IniFlu_1.0.xlsm file in the absolute path C:\Flutures\FluConvert\Output

Usage
1.Strain-based amino acid sequence alignment
 1.1 Open IniFlu_1.0.xlsm (If the security alerts on the Message Bar, click Enable Macro)
 1.2 Select "Sequence Data Processing" Tab → "FluCS" → Click "Input all standard viral nomenclature"
 1.3 Next, click the menu "Input segment viral nomenclature" → a virus protein
 1.4 Then click FluCS → a virus protein
     Repeat 1.3 ~ 1.4 until all virus proteins are imported.

2.Sequence processing
 2.1 Select "Sequence Grouping and Computing" Tab → "Calculate the mother group consensus"
 2.2 Select "Sequence Data Processing" Tab → "Sequence Processing" → "Residue annotate" menu → a virus protein
 2.3 Next, click the menu "Hide UTP" → a virus protein
     Repeat 1.3 ~ 1.4 until all virus proteins are processed. 
     (If some residues are hidden and you want to show, you can use mouse right-click menu to show the column.)
 
3.Sequence grouping
 3.1 Select "Sequence Grouping and Computing" Tab → Click "Grouping filter"
 3.2 Click the "▼" on your interest information or resides to make a group.
 3.3 Click "Calculate the daughter group consensus" and type the group file name.
     The file will be save in the C:\Flutures\FluConvert\Output folder.
 3.4 Click "Create a substitution table (strains or %)" to calculate the frequency of amino acids occurring.