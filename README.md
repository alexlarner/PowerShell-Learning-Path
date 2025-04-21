# PowerShell Learning Path

## Tools

- PowerShell 7
    - Install it through the [MSI](https://github.com/PowerShell/PowerShell/releases/download/v7.3.2/PowerShell-7.3.2-win-x64.msi) on its [GitHub releases page](https://github.com/PowerShell/PowerShell/releases), not through winget. Installing PowerShell 7 specifically, from `winget` can cause PowerShell profile permissions errors that are extremely hard to troubleshoot.
- VSCode
    - Install it from winget via Command Prompt or PowerShell via `winget install Microsoft.VisualStudioCode -h`
    - Use this instead of the deprecated PowerShell ISE
    - Here are some YouTube videos on using VSCode for PowerShell
        - [Optimizing Visual Studio Code for Powershell Development by Justin Grote](https://www.youtube.com/watch?v=uoBptbPFOPk)
        - [Using Visual Studio Code as Your Default PowerShell Editor by Tyler Leonhardt](https://www.youtube.com/watch?v=bGn45vIeAMM)
- Windows Terminal
    - Use this so you can have multiple shell tabs on the same window and for different languages (Command Prompt, Python, PowerShell 5, PowerShell 7, etc.)
    - Install it from winget via Command Prompt or PowerShell via `winget install Microsoft.WindowsTerminal -h`
    - Check out its launch presentation [here](https://www.youtube.com/watch?v=KMudkRcwjCw)

## Syllabus

1. Work through [PowerShell in a Month of Lunches](https://www.manning.com/books/learn-powershell-in-a-month-of-lunches) book
1. Work through [PowerShell Scripting in a Month of Lunches](https://www.manning.com/books/learn-powershell-scripting-in-a-month-of-lunches) book
1. Work through [The PowerShell Practice Primer](https://leanpub.com/psprimer)
1. Watch Don Jones' Toolmaking Presentation
    - [Don Jones Toolmaking Part 1 3](https://www.youtube.com/watch?v=KprrLkjPq_c)
    - [Don Jones Toolmaking Part 2 3](https://www.youtube.com/watch?v=U849a17G7Ro)
    - [Don Jones Toolmaking Part 3 3](https://www.youtube.com/watch?v=GXdmjCPYYNM)
1. Work through [The PowerShell Scripting and Toolmaking Book](https://leanpub.com/powershell-scripting-toolmaking)

## Reference Material

- [PowerShell Style Guide](https://github.com/PoshCode/PowerShellPracticeAndStyle/blob/master/Style-Guide/Introduction.md)
- [PowerShell Deep Dives](https://docs.microsoft.com/en-us/powershell/scripting/learn/deep-dives/overview?view=powershell-7.3)
- [PowerShell Reference](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/?view=powershell-7.3)
- [Deep Dive into PowerShell's Core Building Blocks](https://powershell.one/fundamentals)
- [PowerShell Strategies](https://powershell.one/strategies)
- [Sample Code](https://powershell.one/code)
- [Adam the Automator Tutorials](https://adamtheautomator.com/tutorials/?_tags=powershell)

## Topical

### Books

[DevOps Collective Books](https://leanpub.com/u/devopscollective), which are all free, especially:

- [The Big Book of PowerShell Gotchas](https://leanpub.com/thebigbookofpowershellgotchas)
- [The Big Book of PowerShell Error Handling](https://leanpub.com/thebigbookofpowershellerrorhandling)

PowerShell Conference Books

- [Volume 1](https://leanpub.com/powershell-conference-book)
- [Volume 2](https://leanpub.com/psconfbook2)
- [Volume 3](https://leanpub.com/psconfbook3)
- [Modern IT Automation with PowerShell - First Edition](https://leanpub.com/modernautomationwithpowershell)

### Videos

I highly recommend the [PowerShell.org](https://www.youtube.com/@PowershellOrg) and the [PowerShell Conference EU](https://www.youtube.com/@PowerShellConferenceEU/videos) YouTube Channels. They have lots of useful content for all experience levels, from beginner to expert. All of the below videos are from those channels.

- IDE
    - [Using Visual Studio Code as your Default PowerShell Editor](https://www.youtube.com/watch?v=LF0Srh9hxj8)
    - [Optimizing Visual Studio Code for PowerShell, 2023 Edition](https://youtu.be/1Tk8n47xiIA)
- Best Practices
    - [Writing Award Winning PowerShell Functions and Script Modules by Mike Robbins](https://www.youtube.com/watch?v=d5x0Di52QZA)
- Parameters
    - [Become a parameter ninja by James O'Neill](https://www.youtube.com/watch?v=LMw_mfYRHYI)
    - [Parameter Binding & Type Conversion by Friedrich Weinmann](https://www.youtube.com/watch?v=eccKZIFMX0Q)
        - [ScriptTransformation Attribute](https://psframework.org/documentation/documents/psframework/utility/ScriptTransformation.html)
- Pipeline
    - [Enter the Pipeline by Friedrich Weinmann](https://youtu.be/z1rgaMzBdEk?t=2049)
        - This [article](https://powershell.one/powershell-internals/scriptblocks/powershell-pipeline) is a bit easier to follow.
- Error Handling
    - [When bad things happen to good scripts. Error handling in PS](https://www.youtube.com/watch?v=Wfl1dXI06y8)
- Debugging
    - [Become a PowerShell Debugging Ninja by Kirk Munro](https://www.youtube.com/watch?v=zhjU24hbYuI)
- Module Creation
    - [ModuleBuilder Module](https://github.com/PoshCode/ModuleBuilder)
- RestAPI
    - [From API to usable PowerShell module by James O'Neill](https://www.youtube.com/watch?v=OUZAsf0s9EE)
    - [AutoRest: The Module Generator by Anthony Howell](https://www.youtube.com/watch?v=g6K7yvELCR8&list=PLxBMu7DSsSbDdlJsehI273YOD3rN6ZJIw)
- Classes
    - [Developing with PowerShell Classes: Here be Dragons by Brandon Olin](https://www.youtube.com/watch?v=i1DpPU_xxBc)
- Speed Optimization
    - [High-Intensity Scripting: Revisiting Speed Optimizations with PowerShell 7](https://www.youtube.com/watch?v=NsRoz3JmKUM)

## Useful Modules

- [Microsoft Graph++](https://github.com/jhoneill/MsftGraph)
    - User-friendly wrapper around the auto-generated [PowerShell Graph SDK](https://learn.microsoft.com/en-us/powershell/microsoftgraph/overview?view=graph-powershell-1.0) commands to make them follow PowerShell best practices
    - [Demo Talk](https://www.youtube.com/watch?v=L_7ItIa70HE)
- [ImportExcel](https://github.com/dfinke/ImportExcel)
    - Create, Import, Edit, and Export Excel spreadsheets with PowerShell
    - [Demo Talk](https://www.youtube.com/watch?v=0bR-8b6OMTk)
    - [VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=DougFinke.powershellexcel-snippets)
- [Profiler](https://github.com/nohwnd/Profiler)
    - Script, ScriptBlock and module performance profiler for PowerShell 5, and PowerShell 7 that works in Windows, Linux and MacOS.
    - [Demo Talk](https://youtu.be/1z-UXw51EPU)
- [PSFramework](https://github.com/PowershellFrameworkCollective/psframework)
    - The best solution for PowerShell logging and so much more
    - [Demo Talk](https://youtu.be/Uy5Qd9g25Dg)
    - [Documentation](https://psframework.org/documentation.html) (Yes it is spotty in places)
- [PlatyPS](https://github.com/PowerShell/platyPS)
    - Create Markdown help from comment-based help
    - Create updateable help (MAML format) from those Markdown files
    - Check out these articles on how to format those Markdown files:
        - [Schema](https://github.com/PowerShell/platyPS/blob/master/platyPS.schema.md)
        - [Markdown best practices](https://learn.microsoft.com/en-us/powershell/scripting/community/contributing/general-markdown)
        - [PowerShell-Docs style guide](https://learn.microsoft.com/en-us/powershell/scripting/community/contributing/powershell-style-guide)
        - [Editorial checklist](https://learn.microsoft.com/en-us/powershell/scripting/community/contributing/editorial-checklist)

## Blogs

- [Mike F. Robbins](https://mikefrobbins.com/tags/powershell/)
- [PDQ](https://www.pdq.com/blog/categories/powershell/1/)
- [PowerShell.org](https://powershell.org/articles/)
- [The Lonely Administrator](https://jdhitsolutions.com/blog/)

## Discord Servers

- [PDQ - PowerShell Thread](https://discord.gg/pdq)
- [PowerShell](https://discord.com/invite/powershell)
- [WinAdmins - PowerShell Thread](https://discord.com/invite/winadmins)

## Misc

[PowerShell Podcast](https://www.youtube.com/playlist?list=PL1mL90yFExsjUS8DRkzfLUcHds7vlxqgM)
