Disclaimer: Please note that we no longer support older versions of SDKs and Modules. We recommend that the latest versions are used.

# README

# Contents

- Introduction
- Prerequisites
- Installing the payment module
- License

# Introduction

This X-Cart module provides an easy method to integrate with the payment gateway.
 - The httpdocs directory contains the files that need to be uploaded to the root of your X-Cart installation
 - Supports X-Cart versions: **5.3+**

# Prerequisites

- The module requires the following prerequisites to be met in order to function correctly:
    - The 'bcmath' php extension module: https://www.php.net/manual/en/book.bc.php
    
> Please note that we can only offer support for the module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarantee normal functionality if unsupported changes are made.

# Installing and configuring the module

1. Copy and paste the contents of httpdocs to your root X-Cart
2. Log in to your admin panel and navigate to System Settings -> Cache Management and click 'redeploy store'
3. Navigate to modules and locate Cardstream and click the 'install' button, the store will redeploy again automatically
4. Click settings under the Cardstream module you just installed
5. Under 'Online Payments' click 'Add Payment Method'. Locate and add Cardstream
6. Configure the Cardstream payment gateway and click 'save'. Now you should be able to see and checkout using the Cardstream payment gateway

License
----
MIT
