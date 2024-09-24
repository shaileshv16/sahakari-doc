**Society Registration**

Society Registration will be done by the Automation Cloud Solutions Marketing Dept.
**Step 1.** Login - AisCenterApp
   Menu -> Register-Sahakari Tenant Registration

- Society Name
- Ais CustomerId
- Address
- Company If Needed
- IsFundOutTran is Required for Fund Transfer



**Customer Registration**
Customer Registration is mandatory whoever using the Sahakari App
To Register Customer member of a Society follow below mentioned steps...

- Login SmartBank
- Goto File-Mobile/Web App Connector
- Login to AisCenterApp
- Select Registration->SahakariApp Registration
- Click on New Sahakari App
- Select the Customer Member
- Select A/c Head and A/c No
- Save


**Step 2.** Verification of Customer

- Login With different UserName in SmartBank
- File-> Mobile/Web App Connector -> Login AisCenterApp
- Goto Menu Registration->Sahakari App Registration->Select the Customer/Party and Verify the same.

**Step 3.** Allow NEFT to Other Bank option / Bills Payment
- Contact Automation Service supprt
E.g: 
update DigiPayBank
set IsUtilityPay='1', IsFundOutTran='1'
where DigiPartyId='274379' 

   


 