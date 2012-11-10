easyphp-codetester-fix
======================

Security fix for EasyPHP's Code Tester functionality

As discussed on the EasyPHP forum (12.1 section), these files will add nonce functionality to the code tester part of the EasyPHP admin page.

This will (should) stop the remote exploit that o2326570 discovered.

See the article for more info: http://www.easyphp.org/forums/52/151031/12_1_security_vulnerability__remote_execution_of_php_js__full_compromise_of_your_pc_

I've not hosted all the source code for the EasyPHP admin area, just the files that need to be modified to get the nonce protecting your PC.  

In the forum post I highlighted what needed to be done, this is just for those not overly comfortable modifying the code themselves.  Download it and replace the files that are in the EasyPHP-12.1/home directory.  As always, make back ups of the files first and use at your own risk.