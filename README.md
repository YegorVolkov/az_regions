### <u>Table of Azure Physical Regions</u>

Following table listing Azure regions that are classified as physical regions.

These are the regions where Azure data centers are physically located and where resources can be deployed.

### <u>Creating the list</u>

You can recreate the list using this command:

```pwsh
az account list-locations --query "[?metadata.regionType == 'Physical']" -o table
```

### <u>Results</u>

```pwsh
DisplayName           Name                RegionalDisplayName
--------------------  ------------------  ----------------------------------
East US               eastus              (US) East US
South Central US      southcentralus      (US) South Central US
West US 2             westus2             (US) West US 2
West US 3             westus3             (US) West US 3
Australia East        australiaeast       (Asia Pacific) Australia East
Southeast Asia        southeastasia       (Asia Pacific) Southeast Asia
North Europe          northeurope         (Europe) North Europe
Sweden Central        swedencentral       (Europe) Sweden Central
UK South              uksouth             (Europe) UK South
West Europe           westeurope          (Europe) West Europe
Central US            centralus           (US) Central US
South Africa North    southafricanorth    (Africa) South Africa North
Central India         centralindia        (Asia Pacific) Central India
East Asia             eastasia            (Asia Pacific) East Asia
Japan East            japaneast           (Asia Pacific) Japan East
Korea Central         koreacentral        (Asia Pacific) Korea Central
Canada Central        canadacentral       (Canada) Canada Central
France Central        francecentral       (Europe) France Central
Germany West Central  germanywestcentral  (Europe) Germany West Central
Italy North           italynorth          (Europe) Italy North
Norway East           norwayeast          (Europe) Norway East
Poland Central        polandcentral       (Europe) Poland Central
Spain Central         spaincentral        (Europe) Spain Central
Switzerland North     switzerlandnorth    (Europe) Switzerland North
Mexico Central        mexicocentral       (Mexico) Mexico Central
UAE North             uaenorth            (Middle East) UAE North
Brazil South          brazilsouth         (South America) Brazil South
Israel Central        israelcentral       (Middle East) Israel Central
Qatar Central         qatarcentral        (Middle East) Qatar Central
Brazil US             brazilus            (South America) Brazil US
East US 2             eastus2             (US) East US 2
East US STG           eastusstg           (US) East US STG
North Central US      northcentralus      (US) North Central US
West US               westus              (US) West US
Japan West            japanwest           (Asia Pacific) Japan West
Jio India West        jioindiawest        (Asia Pacific) Jio India West
Central US EUAP       centraluseuap       (US) Central US EUAP
East US 2 EUAP        eastus2euap         (US) East US 2 EUAP
West Central US       westcentralus       (US) West Central US
South Africa West     southafricawest     (Africa) South Africa West
Australia Central     australiacentral    (Asia Pacific) Australia Central
Australia Central 2   australiacentral2   (Asia Pacific) Australia Central 2
Australia Southeast   australiasoutheast  (Asia Pacific) Australia Southeast
Jio India Central     jioindiacentral     (Asia Pacific) Jio India Central
Korea South           koreasouth          (Asia Pacific) Korea South
South India           southindia          (Asia Pacific) South India
West India            westindia           (Asia Pacific) West India
Canada East           canadaeast          (Canada) Canada East
France South          francesouth         (Europe) France South
Germany North         germanynorth        (Europe) Germany North
Norway West           norwaywest          (Europe) Norway West
Switzerland West      switzerlandwest     (Europe) Switzerland West
UK West               ukwest              (Europe) UK West
UAE Central           uaecentral          (Middle East) UAE Central
Brazil Southeast      brazilsoutheast     (South America) Brazil Southeast
```