**First API**: This API retrieves all the arrivals and Guest in House data, along with Country codes, Region Codes, and Nationality Codes. Note that you can't insert any codes into Opera except those built into it.

Endpoint:
`https://api.dominacoralbay.cloud/v2/data.php`

**Parameters**:
- `license_key=demo`
- `list=` (values can be: Arrivals, gih, Country)

Parameters:
- `Arrival` - Retrieves all the arrivals data.
- `gih` - Retrieves all the Guest in House data.
- `Country` - Retrieves all the countries, nationalities, and region codes.

Second API: This API has options to read and write data.

Read:

You can read the required data by providing the confirmation or voucher number along with the last name.

Endpoint:
`https://api.dominacoralbay.cloud/v2/arrivals.php`

Parameters:
- `type=R`
- `license_key=demo`
- `confirmno`
- `Voucher_no`

Write:

Parameters:
- `type=W` -> to Write
- `license_key=demo`
- `last` -> Last Name
- `first` -> First Name
- `gender` -> Gender
- `nationality` -> Nationality Code as built in the Opera
- `region` -> Region Code as built in the Opera
- `birth_date` -> Birthdate
- `name_id` -> Mandatory to select the right data
- `country` -> Country Code as built in the Opera
- `ID_NUMBER` -> Passport Number Or ID Number
- `Email` -> Email Address
- `Phone` -> Phone Number

Third API: For billing, similar to the second API, you can read and write through it.

Endpoint:
`https://api.dominacoralbay.cloud/v2/billing.php`

Read Parameters:
- `type=R`
- `license_key=demo`
- `room` -> Room Number

Write Parameters:
- `type=W`
- `amount - > in EGP`
-  ´method -> CC, RC, Cash ... etc. as built in the Opera System`
- `license_key=demo`
- `tc_group name` -> like SPA, Outlet, Retail, Other, etc.
- `tc` -> Transaction code
- `tax_code1` -> for example Tax transaction code 14%
- `tax_code2` -> for example Tax transaction code 10%
- `tax_code3` -> for example Tax transaction code 1%


Forth API: to read the Guest in House by room number.

Endpoint:
https://api.dominacoralbay.cloud/v2/guestinhouse.php

Read Parameters:
- `license_key=demo`
- `room` -> Room Number
