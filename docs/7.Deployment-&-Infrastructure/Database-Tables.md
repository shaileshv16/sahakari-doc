| Table | Description |
| ----- | ----------- |
| **SahakariTenant** | Society Details Name, Address & Recharge EXT |
| **SahakariTenantEXT** | Neft & BBPS Enable & Disable |
| **DigiPayBill** | When Society added money to automation wallet |
| **DigiParty** | Society Member |
| **DigiPayBank** | Neft & BBPS Enable & Disable |

<br/>



| **SahakariTenant** | **Id** | **AisCustId** | **Name** | **ShortName** | **IconHtml** | **R** | **T** | **Address** | **CreditLimit** | **uid** | **cdt** | **Contact** | **Mid** | **IsPaymentBank** |
| -------------- | --- | --------- | ---- | --------- | -------- | --- | --- | ------- | ----------- | --- | --- | ------- | --- | ------------- |
|  | 1 | 1 | AUTOMATION | AUTOMATION |  | 0 | 0 | BENGALURU | 500 | shilpahere26@outlook.com | 2019-07-24 7:45:07 | AUTOMATION | NULL | 1 |

***

| **SahakariTenantExt** | **Id** | **SahakariTenantId** | **MobileNo** | **Urn** | **CompId** | **ECode** | **BankId** | **cdt** | **R** | **T** | **IsUtilityPay** | **IsCardIntegration** | **IsFundOutTran** |  |  |  |  |  |
| ----------------- | --- | ---------------- | -------- | --- | ------ | ----- | ------ | --- | --- | --- | ------------ | ----------------- | ------------- | --- | --- | --- | --- | --- |
|  | 1 | 1 | 9004035654 | MjYxOF8xMfMjAwNjdfMjAyMw=== | 115625 | NARA | 1814019 | 2022-06-21 15:52:10 | 0 | 0 | 1 | 0 | 1 |  |  |  |  |  |

***

| **DIgiPayBill** | **Id** | **DigiMastId** | **TranType** | **ApiProvider** | **ExtAgentCode** | **DigiOrgId** | **PartymastID** | **Acsubid** | **UserName** | **DigiBillerId** | **APiConsumerNo** | **APIRequestID** | **ApiTranRefId** | **DigiBillBenId** | **Deposit** | **Withdraw** | **CDt** | **R** |
| ----------- | --- | ---------- | -------- | ----------- | ------------ | --------- | ----------- | ------- | -------- | ------------ | ------------- | ------------ | ------------ | ------------- | ------- | -------- | --- | --- |
|  | 704731\_1 | 704731 | BP | BAV | CC01CV74AGTU00000005 | 1 | P2\_1850\_#H | A\_1959\_#H | 9663027279 | BILAVJIO000001 | Mobile Number | YDVNGJNZ3OKEOUPY3I5AXO64C1J41861450 | NULL | NULL | 0 | 149 | 2024-07-04 9:21:08 | 0 |

***

| **DigiPayBank** | **id** | **TranPin** | **DigiPartyId** | **cdt** | **Oid** | **r** | **IsUtilityPay** | **IsFundOutTran** |
| ----------- | --- | ------- | ----------- | --- | --- | --- | ------------ | ------------- |
|  | 105 | 123456 | P2\_95\_#H | 2022-09-02 8:50:17 | Sys | 0 | 1 | 1 |

> ***NOTE:-***
> 
> **IsUtilityPay** = 1, it means that the society member can use BBPS .
> 
> **If IsFundOutTran** = 1, it means that the society member can transfer funds to another bank.

***

| ***DigiParty*** | **Id** | **TenantId** | **PartyMastId** | **Name** | **MobileNo** | **Email** | **R** | **T** | **OID** | **UN** | **UCID** | **UC** | **CDt** | **EDt** | **MId** | **PartyActid** | **PartyNo** | **Sdid** | **DigiOrgid** |
| --------- | :---: | :------: | :---------: | :---: | :------: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--------: | :-----: | :---: | :-------: |
|  | 114151 | 1 | P2\_9738\_#H | Rajesh | 8861513123 | NULL | 0 | 0 | #ADMIN | admin | A | A | 2021-09-03 06:44:23.790 | 2021-09-03 00:14:22.000 | 11 | NULL | 00001003182 | 1 | 1 |
