# Super PAC megadonors data
The data file (megadonor_contributions.csv) contains all contributions from and refunds to people, businesses and organizations that have contributed at least $1 million to super PACs during the 2015-16 election cycle. Super PACs can accept unlimited contributions from donors, including unions and businesses, but are prohibited from coordinating with candidates and their campaigns.

Utilizing an in-house database of electronically filed reports submitted to the Federal Election Commission, the USA TODAY Network identified 156 mega-donors who have given a total of $569.8 million. The data file and analysis include all reports filed with the FEC as of 8/28/2016.

## Fields
Here are descriptions of the fields found in the data file:
* __CommID:__ Committee ID. This is the ID number assigned by the FEC to the Super PAC receiving the contribution (or issuing the refund). You can use this ID number to find the specific report containing the contribution or refund on the [FEC website] (http://www.fec.gov).
* __Committee:__ The name of the Super PAC
* __PAC_view:__ For our analysis, we labeled each Super PAC as leaning Democratic (D), Republican (R), Conservative (C), Liberal (L) or non-partisan (N). We based this decision on independent expenditures, Super PAC websites and, when no other information was available, the political leanings of contributors.
* __Supports:__ When a Super PAC is focused on the White House race, we indicate which candidate was supported in this field. We did not track Super PACs opposed to a specific candidate
* __ContDt:__ Contribution date
* __ContAmt:__ Contribution amount
* __LinkedDonorID:__ Identifier created internally by the USA TODAY Network for a specific mega-donor.
* __LinkedDonor:__ Cleaned up and standardized name for the mega-donor.