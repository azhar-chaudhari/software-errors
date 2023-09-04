# Xampp Errors

### 'c:\xampp\mysql\data\ibtmp1' size to 12 MB. Physically writing the file full; Please wait ...
Can't run XAMPP - MySql

### Answer

```text
  1. Back up "C:\xampp\mysql\data" to "C:\xampp\mysql\data_2" (data_2 can be any name)
  2. Copy all files from "C:\xampp\mysql\backup" to "C:\xampp\mysql\data" ( except for the ibdata1 file )
```
