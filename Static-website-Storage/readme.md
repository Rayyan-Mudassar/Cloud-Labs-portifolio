# Static Website Hosting on Azure storage + CDN
## 1. Created a resource group
Created a resource group named StaticWebsite-Rg to arrange all the resources related to this project and also analyzing the cost which can be used in real scenerios.
Screenshot is attached named ResourceGroupSTWEB.
## 2. Created a Storage account
I created a storage account named storagestaticazure123, it will host a static website and i used blob storage in it and redundancy is set to LRS, Screenshot is attached named storagestaticazure123.
## 3. Enabled Static Website Hosting
In my storage account i created in previous step, i enabled the static website option to makw it able to host a static website, when i enabled this option, it automatically created a container named $web. This will allow my Storage account to serve HTML files. Screenshot is attached named EnableStaticWeb.
## 4. Uploaded Website Files
In this step, i uploaded my static website files, as i am a begineer not an expert so my static website file is also very simple, screenshot is attached named index-error.
