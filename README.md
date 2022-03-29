# Primitive Datatype Activity

### Task 1

##### Use “Get-Help” to find out more information about 5 cmdlets.

```Get-help Get-command```

<img src="https://i.gyazo.com/b4c7bfd9b455fd0bfb59b109fa2a38ec.png">

```Get-help Set-ExecutionPolicy```

<img src="https://i.gyazo.com/84c58396545127aedc3c91d4a9f8a44b.png">

```Get-help ConvertTo-HTML```

<img src="https://i.gyazo.com/2d6717ef2f63fd79e5f39ac63490d4e7.png">

```Get-help Get-EventLog```

<img src="https://i.gyazo.com/664ac73e621a438cd3656ea878bb51b5.png">

```Get-help Get-Process```

<img src="https://i.gyazo.com/fe9936a5c4c805926a2f1491efcdd2e8.png">

### Task 2

##### Use “Get-Help” with the “–Example” parameter for the 5 cmdlets you discovered more about in task 1.

```Get-help -name Get-command -Examples```

<img src="https://i.gyazo.com/a33b70f18c283988144bd7c014ae0c2c.png">

```Get-help -name Set-ExecutionPolicy -Examples```

<img src="https://i.gyazo.com/585cdebe31ca315d8b7b91821ff03735.png">

```Get-help -name ConvertTo-HTML -Examples```

<img src="https://i.gyazo.com/69bf7115efb5199d319a4f600f87a94d.png">

```Get-help -name Get-EventLog -Examples```

<img src="https://i.gyazo.com/b3f4626ed65db39412be8a2e3e124c2c.png">

```Get-help -name Get-Process -Examples```

<img src="https://i.gyazo.com/be4a1013246069d877e585c79755501e.png">

### Task 3

##### Create a new text file named “TestFile.txt” under C:\Maximo\PowerShell\Workshop1\%USERNAME%

```New-Item TestFile.txt```

<img src="https://i.gyazo.com/a367ee2268bcbc697313c6eb52f43334.png">

### Task 4

##### Populate the text file you created in task 3 with all three datatypes we’ve covered: “Boolean”, “String” and “Int”

```Add-Content TestFile.txt -value True```

```Add-Content TestFile.txt -value "Hello world!"```

```Add-Content TestFile.txt -value 10```

<img src="https://i.gyazo.com/0b44ed555754b343de333c3091dc6c2f.png">

### Task 5

##### Read from the text file and use “Get-Member” to find the datatype returned

```Get-Content -path TestFile.txt | Get-member```

<img src="https://i.gyazo.com/01d235378f1206bc42c7ddac7dc675be.png">

### Task 6

##### Overwrite all data within the text file that you created in task 3.

```Set-Content -Path TestFile.txt -Value "Booooo"```

<img src="https://i.gyazo.com/c7efb4727c764d2d876d4fefd697d4c1.png">

### Task 7

##### Format the data returned by a cmdlet into a list

```Get-Service | Format-list```

<img src="https://i.gyazo.com/7c0028be7e0e67ee2205512bd1e9c037.png">

### Task 8

##### Pipe “Get-Command” into “Out-GridView”

```Get-Command | Out-GridView```

<img src="https://i.gyazo.com/83391672c6160df5ab82a156101f8e6f.png">

### Task 9

##### Pipe the 5 cmdlets you discovered in task 1 into “Out-GridView”

```Get-command | Out-GridView```

<img src="https://i.gyazo.com/403f87aa49f0b58e630f4f43487505a2.png">

```Set-ExecutionPolicy | Out-GridView```

<img src="https://i.gyazo.com/5984aba9ae76e28626872c738a43c44c.png">

```ConvertTo-HTML | Out-GridView```

<img src="https://i.gyazo.com/45bcb8f3a57cbe50c5b454c270aff6c3.png">

```Get-EventLog | Out-GridView```

<img src="https://i.gyazo.com/2b492ccff57ad717df1d28ff66f93322.png">

```Get-Process | Out-GridView```

<img src="https://i.gyazo.com/5a8d62298eb3968f50c31664216f76cc.png">

### Task 10

##### Find the official PowerShell documentation library from Microsoft

```https://docs.microsoft.com/es-es/powershell/```

<img src="https://i.gyazo.com/3be938967c553d5b849b4e6a02a0b544.png">


