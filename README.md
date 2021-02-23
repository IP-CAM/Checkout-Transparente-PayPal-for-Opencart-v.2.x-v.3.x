Übersetzungstypen
Textübersetzung
Ausgangstext
2888 / 5000
Übersetzungsergebnisse
# PayPal Transparent Checkout for OpenCart 2 and 3
! [] (https://raw.githubusercontent.com/wiki/paypal/PayPal-PHP-SDK/images/homepage.jpg)

The experience of a Transparent Checkout processed with the security of PayPal. Your customer makes the payment directly on your website, without redirection and without the need to open a PayPal account, using credit card data, which can be saved to speed up the payment process. payment on future purchases.


## Requirements

For the correct functioning of the solutions, it is necessary to check if your store and server support some features:
1. For transparent checkout (PayPal Plus), your store needs to support the CPF (Account type) and Number (Address type) fields, so before activating the solution, ensure that your store is properly configured to support these fields;
2. The server must support PHP 7.3 or higher;
3. The server must support TLS 1.2 or higher and HTTPS 1.1 [(Official Reference)] (https://www.paypal.com/sg/webapps/mpp/tls-http-upgrade).

## Transparent Checkout (PayPal Plus)

The Transparent Checkout is only available for PayPal accounts registered with CNPJ (Corporate Account), if your account is for an individual, you must open a PayPal account for a legal person through this [link] (https://www.paypal.com / bizsignup /).

The solution requires commercial approval, contact 0800 721 6959 and request now.

*** The Transparent Checkout will only work if it has been approved by PayPal. **

## Compatibility

This module is compatible with OpenCart versions 2.0.1.1 to 3.0.3.6.

## Installation

1. Download the module compatible with your version of OpenCart, then access your store administration;
2. Go to the menu ** Extensions → Installer **, click on the "** Upload **" button, locate the file you downloaded, and wait for the automatic installation to complete;
3. Go to the menu ** Extensions → Modifications ** and click on the "** Update **" button;
4. In OpenCart 3, go to the menu ** Control panel **, on the right side of the screen under the button "** Exit **", click on the button in blue with the design of a white gear on it, in modal click on the two orange buttons inside the "** Action **" column to update the theme cache;
5. Go to the menu ** Extensions → Payments ** (in versions 2.3 or higher go to the menu ** Extensions → Extensions ** and filter for ** Payments **), find the extension "** PayPal Plus **", click the "** Install **" button, then the "** Edit **" button, fill in the fields and click the "** Save **" button.

## Settings
### - API Credentials
To configure PayPal solutions, you must generate REST-type API credentials, in this case Client ID and Secret ID.

To obtain them follow this step-by-step:
                
1. Log in with your PayPal account at https://developer.paypal.com and click on the link at the top "** Dashboard **"; 
2. Click on "** My Apps & Credentials **";
3. Under "** Rest API apps **" click "** Create App **";
4. Then enter the term "** ppplus **" in the "** App Name **" field and click "** Create App **";
5. In the upper right corner of the screen, click "** Live **";
6. You must copy the codes that appear in "** Client ID **" and in "** Secret **" (to view the "Secret" it will be necessary to click "** Show **") and paste these codes on the configuration page of the solution you will use.

### - Solution

For Transparent Checkout to work, your store will need to have registered the CPF (Account type) and Number (Address type) fields.

To register them, follow this step-by-step within your OpenCart administrative panel:

Go to the menu ** Customers → Customize registration **, and click on the ** New ** button.

To register the ** CPF **, complete the form with the information below:

| Field | Value |
| -------- | ----- |
| Field name | CPF |
| Location | Account |
| Field type | Text on a line |
| Customer type | Mark the types of customers that will see the field during registration |
| Mandatory types | Check the types of customers that will have the field as mandatory |
| Situation | Enabled |

After completing the form, click on the ** Save ** button.

To register the ** Number **, click the ** New ** button again and fill out the form with the information below:

| Field | Value |
| -------- | ----- |
| Field name | Number |
| Location | Address |
| Field type | Text on a line |
| Customer type | Check the types of customers that will see you during registration |
| Mandatory types | Check the types of customers that will have the field as mandatory |
| Situation | Enabled |

After completing the form, click on the ** Save ** button.

## Questions / Support

If your question has not been answered here, please contact PayPal at 0800 047 4482.

And if you need any technical support and / or believe you have encountered a problem with this module, visit our [technical support portal] (https://www.paypal-support.com/s/?language=pt_BR) and open a ticket detailing your problem in the "Contact Us" section.

## Changelog

To view the latest updates, access [** CHANGELOG.md **] (CHANGELOG.md). 
