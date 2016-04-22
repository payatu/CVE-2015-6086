From Crash to Exploit: CVE-2015-6086 - Out of Bound Read/ASLR Bypass
===================================================================

     $$$$$$\  $$\    $$\ $$$$$$$$\       $$$$$$\   $$$$$$\    $$\  $$$$$$$\          $$$$$$\   $$$$$$\   $$$$$$\
    $$  __$$\ $$ |   $$ |$$  _____|     $$  __$$\ $$$ __$$\ $$$$ | $$  ____|        $$  __$$\ $$$ __$$\ $$  __$$\
    $$ /  \__|$$ |   $$ |$$ |           \__/  $$ |$$$$\ $$ |\_$$ | $$ |             $$ /  \__|$$$$\ $$ |$$ /  $$ |
    $$ |      \$$\  $$  |$$$$$\ $$$$$$\  $$$$$$  |$$\$$\$$ |  $$ | $$$$$$$\ $$$$$$\ $$$$$$$\  $$\$$\$$ | $$$$$$  |
    $$ |       \$$\$$  / $$  __|\______|$$  ____/ $$ \$$$$ |  $$ | \_____$$\\______|$$  __$$\ $$ \$$$$ |$$  __$$<
    $$ |  $$\   \$$$  /  $$ |           $$ |      $$ |\$$$ |  $$ | $$\   $$ |       $$ /  $$ |$$ |\$$$ |$$ /  $$ |
    \$$$$$$  |   \$  /   $$$$$$$$\      $$$$$$$$\ \$$$$$$  /$$$$$$\\$$$$$$  |        $$$$$$  |\$$$$$$  /\$$$$$$  |
     \______/     \_/    \________|     \________| \______/ \______|\______/         \______/  \______/  \______/
------------------------------------------------------------------------------------------------------------------


**Copyright 2016 © Payatu Technologies Pvt. Ltd.**


Improper handling of new line and white space character caused Out of Bound Read in **`CDOMStringDataList::InitFromString`**.
This flaw can be used to leak the base address of **`MSHTML.DLL`** and effectively bypass **`Address Space Layout Randomization`**.


Affected Version
-----------------
* **Internet Explorer 9**
* **Internet Explorer 10**
* **Internet Explorer 11**


Test Bed
--------
* **IE: 10 & 11**
* **KB: KB3087038**
* **OS: Windows 7 SP1 x86**


Advisory
--------
* [**http://www.payatu.com/advisory-ie_cdomstringdatalist/**](http://www.payatu.com/advisory-ie_cdomstringdatalist/)
* [**https://technet.microsoft.com/library/security/MS15-112**](https://technet.microsoft.com/library/security/MS15-112)
* [**http://www.zerodayinitiative.com/advisories/ZDI-15-547/**](http://www.zerodayinitiative.com/advisories/ZDI-15-547/)


Blog Post
---------
[**http://www.payatu.com/from-crash-to-exploit/**](http://www.payatu.com/from-crash-to-exploit/)


Author
------

> **Ashfaq Ansari**

> ashfaq[at]payatu[dot]com

> **[@HackSysTeam](https://twitter.com/HackSysTeam) | [Blog](http://hacksys.vfreaks.com/ "HackSys Team") | [null](http://null.co.in/profile/411-ashfaq-ansari)**

> ![Payatu Technologies](http://www.payatu.com/wp-content/uploads/2015/04/Payatu_Logo.png "Payatu Technologies Pvt. Ltd.")

> [http://www.payatu.com/](http://www.payatu.com/ "Payatu Technologies Pvt. Ltd.")


Workshop Conducted
------------------
* [**From Crash to Exploit: CVE-2015-6086**](https://null.co.in/events/158-pune-null-pune-humla-16-january-2016-from-crash-to-exploit)

------------------------------------------------------------------------------------------------------------------


[**http://hacksys.vfreaks.com**](http://hacksys.vfreaks.com)

![HackSys Team](http://hacksys.vfreaks.com/wp-content/themes/Polished/images/logo.png)
