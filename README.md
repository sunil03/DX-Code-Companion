# CS SalesforceDX Code Companion

Provides ability to save Apex Classes, Apex Triggers, Visualforce, AuraBundles and ApexComponents to Salesforce org at blazing speed.This extension requires users to have SalesforceDX CLI and also mo-dx-plugin for SalesforceDX CLI.This Extension works with both scratch orgs and Non-scratch orgs.

It is highly recommended to use with Salesforce Extension Pack (https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode) .

## Requirements

This salesforce extension works only once you have installed Salesforce CLI and a custom plugin that has api for all the commands this plugin leverages .

1. Install SalesforceDX CLI from https://developer.salesforce.com/tools/sfdxcli based on your operating system.
2. Install mo-dx-plugin using the command `sfdx plugins:install mo-dx-plugin`
3. Salesforce official plugin provides great syntax and language support .Highly recommend to install (https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode)

## Features

1. **Save Apex Class,Apex Trigger,Visualforce Page and Visualforce Component To Salesforce Org**

Right click on the File and click **_"Save To Salesforce"_**

![Save Apex](./images/saveApex.gif)

2. **Save Lightning Components To Salesforce Org**

Right click on the File and click **_"Save To Salesforce"_**

![Save AuraBundle Files](./images/auraSave.gif)

3. **Retrieve Source In DX format from Managed/Unmamaged Package**

Right click and click **_"Retrieve DX Source From Package"_**. Provide the name of the managed/unmanaged package and press enter .

You will notice that package.xml is autogenerated in the manifest directory and source code of the package is retrieved in DX source format. 

![Retrieve Source From Unmanaged/Managed Package In DX Format](./images/retrieve.png)

## Extension Shortcut Keys

To Save any of the supported files to salesforce you can use the below shorcut keys based on the operating system.

"MACOSX": "cmd+shift+c",
"win": "ctrl+shift+c",
"linux": "ctrl+shift+c",

## Issue Reporting

If you find any issues feel free to log it on the github page for the project @ https://github.com/msrivastav13/DX-Code-Companion/issues

## Release Notes

### 0.0.1

1. Provides quick save apex,vf,aura bundles to salesforce server
2. Retrieve Source from Salesforce using DX Source format.
3. 3X performant than salesforce deploy command for apex , aura and vf files.

-----------------------------------------------------------------------------------------------------------

### For more information and contribution to project visit the below repositories and use issues tab to log any feedback or issues .

* [Mo DX Plugin Repository](https://github.com/msrivastav13/mo-dx-plugin)
* [DX Code Companion](https://github.com/msrivastav13/DX-Code-Companion)

**Enjoy!**