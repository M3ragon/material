# Commands

## "Git"Bash

Compare 2 Files  
[StackExchange](https://unix.stackexchange.com/questions/408644/remove-lines-in-file-1-from-file-2)  

```sh
awk 'NR==FNR {a[$1];next}!($1 in a ) {print $1}' file2 file1
```

## Powershell

Symbolik-Links  

```ps1
New-Item -ItemType Junction -Path $Destination -Target $Target
```

### Winget

Export all Programms:  

```ps1
winget export -o "C:\programme_winget_export.json"
```

Install/Import Programms:  

```ps1
winget import -i "C:\programme_winget_export.json"
```

Upgrade all Programms:  

```ps1
winget upgrade --all
```

---

## CMD

---

## DayZ Helper

Create Types from csv  
Files Template:  

```csv
name,nominal,min,lifetime,restock,quantmin,quantmax,cost,category
AA12_Gun,5,1,7200,0,-1,-1,100,weapons
```

import in [Converter](https://www.convertcsv.com/csv-to-xml.htm) and use "pattern"

```xml
<?xml version="1.0"?>{br}<types>{br}

<type name="{f1}">
  <{h2}>{f2}</{h2}>
  <{h3}>{f3}</{h3}>
  <{h4}>{f4}</{h4}>
  <{h5}>{f5}</{h5}>
  <{h6}>{f6}</{h6}>
  <{h7}>{f7}</{h7}>
  <{h8}>{f8}</{h8}>
  <category name="{f9}"/>
  <flags count_in_hoarder="0" count_in_player="0" count_in_map="1" count_in_cargo="0" crafted="0" deloot="0"/>
</type>{br}

</types>
```

---
