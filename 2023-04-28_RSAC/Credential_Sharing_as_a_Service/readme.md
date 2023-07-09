# Credential Sharing as a Service: the Dark Side of No Code

[View on RSAC 2023 agenda](https://www.rsaconference.com/library/presentation/usa/2023/Credential%20Sharing%20as%20a%20Service%20The%20Dark%20Side%20of%20No%20Code)

## Abstract

Low-code apps have become a reality in the enterprise, with surveys showing that most enterprise apps are now built outside of IT and lacking security practices. Unsurprisingly, attackers have figured out ways to leverage these platforms for their gain. This talk will demonstrate a host of attack techniques found in the wild, where low-code apps are abused during every step in the cyber kill chain.

## Recommended pre-reading materials

- [Store by Zapier vulnerability](https://www.volkis.com.au/blog/security-design-flaw-in-storage-by-zapier/)

- [Power Platform data leakage](https://www.upguard.com/breaches/power-apps)
 
- [Living-of-the-land of Office365](https://www.vectra.ai/blogpost/o365-security-powerautomate-is-the-new-powershell)

- [Gaining persistency on AWS Lambda](https://unit42.paloaltonetworks.com/gaining-persistency-vulnerable-lambdas/)

## Mentioned in the talk

### Tools and Demos

- [ZapCreds](https://github.com/mbrg/zapcreds) - scan Zapier for shared credentials ready for exploit

- [Powerful](https://github.com/mbrg/powerful) - install a backdoor on Power Platform enabling creating, triggering and deleting any arbitrary flow 

- [Power Platform account takeover demo, YouTube](https://youtu.be/vJZpNJRC_10)

### Articles

- [Low-Code / No-Code Security, Dark Reading](https://www.darkreading.com/author/michael-bargury)

- [Hackers Abuse Low-Code Platforms And Turn Them Against Their Owners, Zenity blog](https://www.zenity.io/blog/hackers-abuse-low-code-platforms-and-turn-them-against-their-owners/)

- [The Microsoft Power Apps Portal Data Leak Revisited: Are You Safe Now?, Zenity blog](https://www.zenity.io/blog/the-microsoft-power-apps-portal-data-leak-revisited-are-you-safe-now/)

- [Zapier Storage Exposes Sensitive Customer Data Due to Poor User Choices, Zenity blog](https://www.zenity.io/blog/zapier-storage-exposes-sensitive-customer-data-due-to-poor-user-choices/)

- [Connectors overview, Microsoft Docs](https://docs.microsoft.com/en-us/connectors/connectors)

- [Set-AdminPowerAppApisToBypassConsent, Microsoft Docs](https://docs.microsoft.com/en-us/powershell/module/microsoft.powerapps.administration.powershell/set-adminpowerappapistobypassconsent)

- [Power Automate Management, Microsoft Docs](https://docs.microsoft.com/en-us/connectors/flowmanagement/)

## Talk materials

- [Slides](/2023-04-28_RSAC/Credential_Sharing_as_a_Service/Michael_Bargury_DAS-R06_Credential_Sharing_as_a_Service_The_Dark_Side_of_No_Code.pdf)

- [Video](https://youtu.be/AD0R4qyrh3g)
