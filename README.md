# FluConvert and IniFlu Readme
## 1. Installation
## 1.1 Minimum system requirements
● Microsoft Windows XP (64-bit) or later operating system  
● Microsoft Office 2016 or later (Excel 64-bit)  
● Java 6 or later  
## 1.2 Minimum system requirements
● Microsoft Windows 10 1903 or later operating system  
● Microsoft Office 365 or Office 2019 or later (Excel 64-bit)  
● Java 10 or later (64-bit)  
## 1.3 Installation
Go to EMBOSS website and download ftp://emboss.open-bio.org/pub/EMBOSS/windows/mEMBOSS-6.5.0.0-setup.exe
Go to MAFFT website and download https://mafft.cbrc.jp/alignment/software/mafft-7.450-win64-signed.zip
Unzip mafft-7.450-win64-signed.zip to absolute path C:\mEMBOSS
```
1. Install mEMBOSS-6.5.0.0-setup.exe in the absolute path C:\mEMBOSS
2. Install mafft-win.exe in the absolute path C:\mEMBOSS
3. Install FluConvert_v1-setup.exe in the absolute path C:\Flutures
4. Copy IniFlu_1.0.xlsm file in the absolute path C:\Flutures\FluConvert\Output
```
## 2. Usage
## Sequence processing
```
1.Sequence fasta file (for example: H5N2.fasta) put into C:\Flutures\FluConvert\Input folder
2.Run C:\Flutures\FluConvert\FluConvert.exe
3.Type virus subtype H5N2, then type 1
4."Do you want to translate the sequences to amino acid?", type Y
5.The completed result will be in the C:\Flutures\FluConvert\Output folder
```
FluConvert regarding the selection of viral subtype, we have only tested H5N2, H7N9, and H1N1 at present.
If you have other subtype requirements, please contact us.
## Strain-based amino acid sequence alignment
```
1.Open IniFlu_1.0.xlsm (If the security alerts on the Message Bar, click Enable Macro)
2.Select "Sequence Data Processing" Tab → "FluCS" → Click "Input all standard viral nomenclature"
3.Next, click the menu "Input segment viral nomenclature" → a virus protein
4.Then click FluCS → a virus protein
Repeat step 3~4 until all virus proteins are imported.
```
## Sequence processing
```
1.Select "Sequence Grouping and Computing" Tab → "Calculate the mother group consensus"
2.Select "Sequence Data Processing" Tab → "Sequence Processing" → "Residue annotate" menu → a virus protein
3.Next, click the menu "Hide UTP" → a virus protein
Repeat step 2~3 until all virus proteins are processed. 
(If some residues are hidden and you want to show, you can use mouse right-click menu to show the column.)
```
## Sequence grouping
```
1.Select "Sequence Grouping and Computing" Tab → Click "Grouping filter"
2.Click the "▼" on your interest information or resides to make a group.
3.Click "Calculate the daughter group consensus" and type the group file name.
The file will be save in the C:\Flutures\FluConvert\Output folder.
4.Click "Create a substitution table (strains or %)" to calculate the frequency of amino acids occurring.
```
