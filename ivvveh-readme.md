my settings
```
$params = @{
    VMName = "eve5"
    SourcePath = "C:\Users\Lab\Documents\Win11_24H2_EnglishInternational_x64.iso"
    Edition    = 6
    VhdFormat  = "VHDX"
    DiskLayout = "UEFI"
    SizeBytes  = 200GB
    MemoryAmount = 64GB
    CPUCores = 16
    NetworkSwitch = "Default Switch"
    VHDPath = "D:\eve5"
    UnattendPath = "$PSScriptRoot"+"\autounattend.xml"
    GPUName = "AUTO"
    GPUResourceAllocationPercentage = 20
    Team_ID = ""
    Key = ""
    Username = "Lab"
    Password = "Lab1!"
    Autologon = "true"
}
```

enable all scripts
```
Set-ExecutionPolicy Bypass -Scope LocalMachine -Force
Set-ExecutionPolicy Bypass -Scope CurrentUser -Force
Set-ExecutionPolicy Bypass -Scope Process -Force
```
