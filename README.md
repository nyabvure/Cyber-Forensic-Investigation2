This is a cyber forensic investigation tool that shows a list of all usb devices that ever connected to a machine

The program is written in java implementing a Java library to get a list of all usb storage devices connected to the computer. It works on the two main operating systems Windows, Linux. It might work on MAC OS havent managed to test it 

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_HP&Prod_Officejet_Pro_86&Rev_1.00\8&35be4865&0&CN373D4GJ405KD&0\Properties
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_JetFlash&Prod_Transcend_16GB&Rev_8.07

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_JetFlash&Prod_Transcend_16GB&Rev_8.07\XHLRW9WJ&0
    DeviceDesc    REG_SZ    @disk.inf,%disk_devdesc%;Disk drive
    Capabilities    REG_DWORD    0x10
    Address    REG_DWORD    0x1
    ContainerID    REG_SZ    {796be101-494c-5fd0-9717-eb2c949cddfa}
    HardwareID    REG_MULTI_SZ    USBSTOR\DiskJetFlashTranscend_16GB__8.07\0USBSTOR\DiskJetFlashTranscend_16GB__\0USBSTOR\DiskJetFlash\0USBSTOR\JetFlashTranscend_16GB__8\0JetFlashTranscend_16GB__8\0USBSTOR\GenDisk\0GenDisk
    CompatibleIDs    REG_MULTI_SZ    USBSTOR\Disk\0USBSTOR\RAW\0GenDisk
    ClassGUID    REG_SZ    {4d36e967-e325-11ce-bfc1-08002be10318}
    Service    REG_SZ    disk
    Driver    REG_SZ    {4d36e967-e325-11ce-bfc1-08002be10318}\0002
    Mfg    REG_SZ    @disk.inf,%genmanufacturer%;(Standard disk drives)
    FriendlyName    REG_SZ    JetFlash Transcend 16GB USB Device
    ConfigFlags    REG_DWORD    0x0

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_JetFlash&Prod_Transcend_16GB&Rev_8.07\XHLRW9WJ&0\Device Parameters

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_JetFlash&Prod_Transcend_16GB&Rev_8.07\XHLRW9WJ&0\Device Parameters\MediaChangeNotification

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_JetFlash&Prod_Transcend_16GB&Rev_8.07\XHLRW9WJ&0\Device Parameters\Partmgr
    DiskId    REG_SZ    {15b27a2b-4eb5-11e8-93b2-b4749f715c6c}
    Attributes    REG_DWORD    0x0

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_JetFlash&Prod_Transcend_16GB&Rev_8.07\XHLRW9WJ&0\Properties
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_SAMSUNG&Prod_S5360_Card&Rev_0000

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USBSTOR\Disk&Ven_SAMSUNG&Prod_S5360_Card&Rev_0000\8&2fefdb42&0&0123456789ABCDEF&0
    DeviceDesc    REG_SZ    @disk.inf,%disk_devdesc%;Disk drive
    Capabilities    REG_DWORD    0x0
    Address    REG_DWORD    0x1
    ContainerID    REG_SZ    {eb64fed1-bf28-5ad9-92c5-7483e1dbd2d6}
    HardwareID    REG_MULTI_SZ    USBSTOR\DiskSAMSUNG_S5360_Card______0000\0USBSTOR\DiskSAMSUNG_S5360_Card______\0USBSTOR\DiskSAMSUNG_\0USBSTOR\SAMSUNG_S5360_Card______0\0SAMSUNG_S5360_Card______0\0USBSTOR\GenDisk\0GenDisk
    CompatibleIDs    REG_MULTI_SZ    USBSTOR\Disk\0USBSTOR\RAW\0GenDisk
    ClassGUID    REG_SZ    {4d36e967-e325-11ce-bfc1-08002be10318}
    Service    REG_SZ    disk
    Driver    REG_SZ    {4d36e967-e325-11ce-bfc1-08002be10318}\0005
    Mfg    REG_SZ    @disk.inf,%genmanufacturer%;(Standard disk drives)
    FriendlyName    REG_SZ    SAMSUNG S5360 Card USB Device
    ConfigFlags    REG_DWORD    0x0
