# Object-Folder for AL-Objects

## Object-Names and Name-property
### New Objects  
Filename [*`Name w.o. blanks or special characters`*][*`Type-Abbreviation`*].`al`  
Name "SIT`<blank>`[*`Name w.o. blanks or special characters`*][*`Type-Abbreviation`*]"  

#### Example  
- Filename `ContactDepartmentTab.al`  
Objectname `ContactDepartmentTab`
- Filename `ContactDepartmentsPag.al`  
Objectname `ContactDepartmentsPag`

### Extension-Objects  
Filename [*`Original Objectname w.o. blanks or special characters`*][*`PageExt|TabExt`*].`al`  
Name "SIT`<blank>`[*`Original Objectname w.o. blanks or special characters`*][*`PagExt|TabExt`*]"  

Reduce Name to <= 30 characters by shortening the Name from the left of PagExt/TabExt

#### Example  
- Extending Table 5050 Contact  
Filename: `ContactTabExt.al`  
Name: "SIT ContactTabExt"  

- Extending Page 5052 Contact List  
Filename `ContactListPagExt.al`  
Name: "SIT ContactListPagExt" 


### Type map
Use the listed abbreviations for each type of object in the file naming:  

| Object | Abbreviation |  
| --- | --- |
| Page | Pag |  
| Page Extension | PagExt |
| Page Customization | PagCust |
| Codeunit | Cod |
| Table | Tab |
| Table Extension | TabExt |
| XML Port | Xml |
| Report | Rep |
| Query | Que |
| Enum | Enu |
| Enum Extension | EnuExt |
