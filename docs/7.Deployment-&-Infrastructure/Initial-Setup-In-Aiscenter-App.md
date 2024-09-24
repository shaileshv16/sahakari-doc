**Society Registration**

Society Registration will be done by the Automation Cloud Solutions Marketing Dept.
**Step 1.** Login - AisCenterApp
   Menu -> Register-Sahakari Tenant Registration

- Society Name
- Ais CustomerId
- Address
- Company If Needed
- IsFundOutTran is Required for Fund Transfer

![SocReg.jpg](/.attachments/SocReg-797ee018-e2a0-4bd1-849f-b1849ff840bf.jpg)

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

![CustReg.jpg](/.attachments/CustReg-de34f388-8794-485e-8db3-c95ec08ee0d5.jpg)

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

   


 