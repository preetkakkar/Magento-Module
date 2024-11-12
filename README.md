## Magento2 Programmatically Add New Customer Input Field on Customer Registration Form

In this extension we have added an input field named "ABN" on the registration page & displayed its value in the admin customer grid.

&nbsp;
&nbsp;

## Description:
This module adds a custom field to the customer registration form, allowing the store to collect additional information during customer sign-up. The new field can be customized to capture any specific data needed by the business, such as "Company Name," "ABN," or other relevant details.

Key features:<br />
Customizable Extra Field: Adds an additional input field to the registration form, which can be tailored to the store's requirements.<br />
Seamless Integration: Integrates with the Magento registration process, ensuring a smooth experience for customers.<br />
Data Storage and Management: The information entered in the extra field is stored in the customer database, making it easy for admins to access and manage this data in the customer profile.<br />
<br />
This module is ideal for businesses needing more information from customers at registration, helping them personalize service or streamline processes based on collected data.

## Installation Steps

##### Step 1 : Download the Zip file from Github & Unzip it
##### Step 2 : Create a directory under app/code/Magento-Module/CustomFieldOnRegistration
##### Step 3 : Upload the files & folders from extracted package to app/code/Magento-Module/CustomFieldOnRegistration
##### Step 4 : Go to the Magento2 Root directory & run following commands

php bin/magento setup:upgrade

php bin/magento setup:di:compile

php bin/magento setup:static-content:deploy -f

php bin/magento cache:flush

&nbsp;
&nbsp;

## Note : We have tested this option in Magento ver. 2.4.6
