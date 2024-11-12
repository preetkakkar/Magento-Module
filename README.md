## Magento2 Programmatically Add New Customer Input Field on Registration Page

> Magento2 an open-source e-commerce platform written in PHP.

&nbsp;
&nbsp;

> Here in this extension we are going to learn how to add new customer input field on Registration page.

&nbsp;
&nbsp;

> In this extension we have added an input field named "ABN" on the registration page & displayed its value in the admin customer grid.

&nbsp;
&nbsp;

##Description:
This module adds a custom field to the customer registration form, allowing the store to collect additional information during customer sign-up. The new field can be customized to capture any specific data needed by the business, such as "Company Name," "ABN," or other relevant details.

Key features:

    Customizable Extra Field: Adds an additional input field to the registration form, which can be tailored to the store's requirements.
    Seamless Integration: Integrates with the Magento registration process, ensuring a smooth experience for customers.
    Data Storage and Management: The information entered in the extra field is stored in the customer database, making it easy for admins to access and manage this data in the customer profile.

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

<h5>Frontend - Customer Registration Page</h5>
<kbd>

![image1](https://user-images.githubusercontent.com/123800304/218378188-905c851e-abf9-46fd-9c34-6d151e80bf03.png)


</kbd>

&nbsp;
&nbsp;

<h5>Admin - Customer Admin Page</h5>
<kbd>


![image2](https://user-images.githubusercontent.com/123800304/218378310-878b8aae-03cb-4406-b61a-252d87b74200.png)


</kbd>

&nbsp;
&nbsp;
## Note : We have tested this option in Magento ver. 2.4.5-p1
