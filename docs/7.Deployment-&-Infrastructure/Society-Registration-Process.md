## Society Registration Process

## Step 1: Society Registration by Automation Cloud Solutions Marketing Dept.

* ***Login to AisCenterApp***
    * Navigate to **Menu -> Register-Sahakari Tenant Registration**.
* **Enter Society Details**
    * **Society Name**: Enter the name of the society.
    * **Ais CustomerId**: Input the AIS Customer ID associated with the society.
    * **Address**: Provide the address of the society.
    * **Company**: 
    * **IsFundOutTran**: Specify whether fund transfer is required.

## Step 2: Customer Registration

**Note**: Customer registration is mandatory for all users of the Sahakari App.

* **Login to SmartBank**
    * Navigate to **File -> Mobile/Web App Connector**.
* **Login to AisCenterApp**
    * Select **Registration -> SahakariApp Registration**.
    * Click on **New Sahakari App**.
* **Register Customer Member**
    * Select the **Customer Member** from the list.
    * Choose the **A/c Head** and **A/c No**.
    * Save the registration.

## Step 3:Verification of Customer

* **Login with a Different Username in SmartBank**
    * Navigate to **File -> Mobile/Web App Connector**.
    * Login to **AisCenterApp**.
* **Verify Customer Registration**
    * Go to **Menu -> Registration -> Sahakari App Registration**.
    * Select the Customer/Party and verify the details.

## Step 4: Enable NEFT to Other Banks and Bill Payment Options

. **Contact Automation Service Support**
* Update the settings for enabling NEFT and Bill Payment options.

**Example query**
`update DigiPayBank
set IsUtilityPay='1', IsFundOutTran='1'
where DigiPartyId='274379';`

This SQL command sets the options to allow NEFT transfers and utility payments for the specified DigiPartyId.


**If BBPS service** is required, then the customer should enroll as a BBPS agent. 
Refer to the spreadsheet below for the customer address, phone number, and other required details when signing up as a BBPS agent.

[Agent Data](https://docs.google.com/spreadsheets/d/1K8OzYM1r6d5BSoDSp5Ae3MLcF82i5-EA/edit?usp=sharing&ouid=105099325201248604326&rtpof=true&sd=true)
