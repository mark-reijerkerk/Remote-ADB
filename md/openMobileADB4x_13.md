##### How to open mobile ADB
Different models of phones may be slightly different!
1. Open system setting app
2. Click 'About phone'
   - <img src="./../image/openMobileAdb/01.png" width="270" height="480">

3. Click on 'Build number' until developer mode is enabled
   - <img src="./../image/openMobileAdb/02.png" width="270" height="480">
   - <img src="./../image/openMobileAdb/03.png" width="270" height="480">

4. Click 'System'
   - <img src="./../image/openMobileAdb/04.png" width="270" height="480">

5. Click 'Developer options'
   - <img src="./../image/openMobileAdb/05.png" width="270" height="480">
   - <img src="./../image/openMobileAdb/06.png" width="270" height="480">

6. Enable 'USB debugging'
   - <img src="./../image/openMobileAdb/07.png" width="270" height="480">

7. Click 'OK'
   - <img src="./../image/openMobileAdb/08.png" width="270" height="480">

8. Connect the USB cable.
9. Click 'Allow'
   - <img src="./../image/openMobileAdb/09.png" width="270" height="480">

10. Click 'Notifications'.
11. Click 'Charging this device via USB'.
    - <img src="./../image/openMobileAdb/10.png" width="270" height="480">

12. Click 'File transfer/Android Auto'
    - <img src="./../image/openMobileAdb/11.png" width="270" height="480">
    
13. Open your PC shell or powershell and input 
    ```
    $ adb devices
    List of devices attached
    HT********	device

    $ adb tcpip 5555
    restarting in TCP mode port: 5555
    ```


