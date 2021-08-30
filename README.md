# oraclewallet
Oracle Wallet for accessing APIs having most commonly used root certificates

Wallet password: manager12

It has following root certificates

$ orapki wallet display -wallet .
Oracle PKI Tool Release 18.0.0.0.0 - Production
Version 18.1.0.0.0
Copyright (c) 2004, 2017, Oracle and/or its affiliates. All rights reserved.

Requested Certificates: 
User Certificates:
Trusted Certificates: 
Subject:        CN=GlobalSign,O=GlobalSign,OU=GlobalSign Root CA - R2
Subject:        CN=USERTrust RSA Certification Authority,O=The USERTRUST Network,L=Jersey City,ST=New Jersey,C=US
Subject:        CN=SecureTrust CA,O=SecureTrust Corporation,C=US
Subject:        CN=Entrust.net Certification Authority (2048),OU=(c) 1999 Entrust.net Limited,OU=www.entrust.net/CPS_2048 incorp. by ref. (limits liab.),O=Entrust.net
Subject:        CN=DigiCert High Assurance EV Root CA,OU=www.digicert.com,O=DigiCert Inc,C=US
Subject:        CN=DigiCert Global CA G2,O=DigiCert Inc,C=US
Subject:        CN=Entrust Root Certification Authority - G2,OU=(c) 2009 Entrust\, Inc. - for authorized use only,OU=See www.entrust.net/legal-terms,O=Entrust\, Inc.,C=US
Subject:        CN=DigiCert Global Root CA,OU=www.digicert.com,O=DigiCert Inc,C=US
Subject:        CN=GlobalSign Root CA,OU=Root CA,O=GlobalSign nv-sa,C=BE
Subject:        CN=DigiCert Global Root G2,OU=www.digicert.com,O=DigiCert Inc,C=US
Subject:        CN=GeoTrust Global CA,O=GeoTrust Inc.,C=US
Subject:        CN=DST Root CA X3,O=Digital Signature Trust Co.
Subject:        CN=Baltimore CyberTrust Root,OU=CyberTrust,O=Baltimore,C=IE
Subject:        CN=COMODO RSA Certification Authority,O=COMODO CA Limited,L=Salford,ST=Greater Manchester,C=GB
Subject:        CN=COMODO ECC Certification Authority,O=COMODO CA Limited,L=Salford,ST=Greater Manchester,C=GB
Subject:        CN=Amazon Root CA 1,O=Amazon,C=US
Subject:        CN=Entrust Certification Authority - L1K,OU=(c) 2012 Entrust\, Inc. - for authorized use only,OU=See www.entrust.net/legal-terms,O=Entrust\, Inc.,C=US
Subject:        CN=VeriSign Class 3 Public Primary Certification Authority - G5,OU=(c) 2006 VeriSign\, Inc. - For authorized use only,OU=VeriSign Trust Network,O=VeriSign\, Inc.,C=US
Subject:        CN=Go Daddy Root Certificate Authority - G2,O=GoDaddy.com\, Inc.,L=Scottsdale,ST=Arizona,C=US


****************************************************************************************************************************************************************
*************************************************************** USING WITH APEX ********************************************************************************
****************************************************************************************************************************************************************

To use this wallet with APEX do following:

1. Go to a directory accessible to oracle user of the operating system (In Linux)
2. Download wallet by running: git clone https://github.com/maxapexcloud/oraclewallet
3. Go to APEX Internal Admin > Manage Instance > Instance Settings > Wallet
4. Type the path of the directory you downloaded wallet in (e.g. file:/home/oracle/wallet). Remember to put file: before the directory
5. Type wallet password (default password of this wallet is manager12)




****************************************************************************************************************************************************************
*************************************************************** MISSING CERTS **********************************************************************************
****************************************************************************************************************************************************************

If you find any certificates missing in the wallet please feel free to let us know and we will add that to the wallet

