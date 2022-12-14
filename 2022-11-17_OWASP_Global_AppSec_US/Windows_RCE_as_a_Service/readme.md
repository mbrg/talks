# Windows RCE as a Service

[View on OWASP Global AppSec US 2022 agenda](https://sched.co/1BS5H)

## Abstract

Windows 11 includes a handy feature called Power Automate Desktop, which lets users automate mundane tasks. In a nutshell, Users can build custom processes and hand them to Microsoft, which in turn ensures they are distributed to all user machines, executed successfully and reports back to the cloud. You can probably already see where this is going..

We will show how Power Automate Desktop can be repurposed to power malware operations. We will demonstrate the full cycle of distributing payloads, bypassing perimeter controls, executing them on victim machines and exfiltrating data. All while using nothing but Windows baked-in and signed executables, and Office cloud services.

We will then take you behind the scenes and explore how this service works and what attack surface it exposes on the machine and in the cloud. We will also point out a few promising future research directions for the community to pursue.

Finally, we will share an open-source command line tool to easily accomplish all of the above, so you will be able to add it into your Red Team arsenal and try out your own ideas.

## Recommended pre-reading materials

- [Living-of-the-land of Office365](https://www.vectra.ai/blogpost/o365-security-powerautomate-is-the-new-powershell)

- [What is RPA](https://powerautomate.microsoft.com/en-us/what-is-rpa/)

### Tools and Demos

- [Power-pwn](https://github.com/mbrg/power-pwn) - install a backdoor on Power Platform enabling creating, triggering and deleting any arbitrary flow 

- [Set up Power Automate Desktop demo, YouTube](https://youtu.be/Kik9oXu_-bI)
 
- [No Code Ransomware demo, YouTube](https://youtu.be/YDull-krSJI)

- [Machine to browser local demo, YouTube](https://youtu.be/lY_RzV-4BdI)

- [Machine to browser cloud demo, YouTube](https://youtu.be/zlF7np18oGI)

### Articles

- [Low-Code / No-Code Security, Dark Reading](https://www.darkreading.com/author/michael-bargury)

- [Power Automate Management, Microsoft Docs](https://docs.microsoft.com/en-us/connectors/flowmanagement/)

- [Silently register a new machine, Microsoft Docs](https://docs.microsoft.com/en-us/power-automate/desktop-flows/machines-silent-registration#silently-register-a-new-machine)
 
- [Power Automate and Windows 11, Microsoft Docs](https://powerautomate.microsoft.com/en-us/power-automate-and-windows-11/)

- [Use browsers and manage extensions, Microsoft Docs](https://docs.microsoft.com/en-in/power-automate/desktop-flows/using-browsers)

- [RPA Architecture, T-Plan](https://www.t-plan.com/rpa-architecture/)

## Talk materials

- [Slides](/2022-11-17_OWASP_Global_AppSec_US/Windows_RCE_as_a_Service/Michael_Bargury_Windows_RCE_as_a_Service.pdf)

- The talk wasn't recoded, but you can find a recording of the same talk from BSides Singapore [here](https://www.youtube.com/watch?v=Y3fKAgQlHvE)
