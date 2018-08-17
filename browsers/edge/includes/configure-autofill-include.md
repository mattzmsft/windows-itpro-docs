<!-- ## Configure Autofill -->
>*Supported versions: Microsoft Edge on Windows 10*<br>
>*Default setting:  Not configured*

[!INCLUDE [configure-autofill-shortdesc](../shortdesc/configure-autofill-shortdesc.md)]

### Supported values

|Group Policy  |MDM |Registry |Description |Most restricted |
|---|:---:|:---:|---|:---:|
|Not configured<br>**(default)** | Blank |Blank |Users can choose to use AutoFill. | |
|Disabled | 0 | no | Prevented. |![Most restricted value](../images/check-gn.png) |
|Enabled |1 |yes | Allowed. | |
---

### ADMX info and settings
#### ADMX info
- **GP English name:** Configure Autofill
- **GP name:** AllowAutofill
- **GP path:** Windows Components/Microsoft Edge
- **GP ADMX file name:** MicrosoftEdge.admx

#### MDM settings
- **MDM name:** Browser/[AllowAutofill](https://docs.microsoft.com/en-us/windows/client-management/mdm/policy-csp-browser\#browser-allowautofill)
- **Supported devices:** Desktop
- **URI full path:** ./Vendor/MSFT/Policy/Config/Browser/AllowAutofill 
- **Data type:** Integer

#### Registry settings
- **Path:** HKLM\\Software\\Policies\\Microsoft\\MicrosoftEdge\\Main
- **Value name:** Use FormSuggest
- **Value type:** REG_SZ

<hr>