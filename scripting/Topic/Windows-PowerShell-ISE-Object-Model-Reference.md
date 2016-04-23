---
title: Windows PowerShell ISE Object Model Reference
ms.custom: na
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: e1a9e7d1-0fd5-47de-8d9b-f1be1ed13b0c
---
# Windows PowerShell ISE Object Model Reference
  
## Object Model Reference
 This section provides a reference on the underlying classes that define the various objects inWindows PowerShellÂ® Integrated Scripting Environment (ISE). To see the objects organized in their hierarchy, see [The ISE Object Model Hierarchy](../Topic/The-ISE-Object-Model-Hierarchy.md).

 [The ISEAddOnTool Object](../Topic/The-ISEAddOnTool-Object.md)
 Examples: $psISE.CurrentVisibleHorizontalTool, $psISE.CurrentVisibleVerticalTool.

 [The ISEAddOnTool Object](../Topic/The-ISEAddOnTool-Object.md)
  [The ISEEditor Object](../Topic/The-ISEEditor-Object.md)
 Examples: $psISE.CurrentFile.Editor, $psISE.CurrentPowerShellTab.Output, $psISE.CurrentPowerShellTab.CommandPane.

 [The ISEFile Object](../Topic/The-ISEFile-Object.md)
 Examples: $psISE.CurrentFile, $psISE.PowerShellTabs.Files\[0\].

 [The ISEFileCollection Object](../Topic/The-ISEFileCollection-Object.md)
 Examples: $psISE.PowerShellTabs.Files.

 [The ISEMenuItem Object](../Topic/The-ISEMenuItem-Object.md)
 Examples: $psISE.CurrentPowerShellTab.AddOnsMenu , $psISE.CurrentPowerShellTab.AddOnsMenu.Submenus\[0\].

 [The ISEMenuItemCollection Object](../Topic/The-ISEMenuItemCollection-Object.md)
 Example: $psISE.CurrentPowerShellTab.AddOnsMenu.Submenus.

 [The ISEOptions Object](../Topic/The-ISEOptions-Object.md)
 Examples: $psISE.Options, $psISE.Options.DefaultOptions.

 [The ObjectModelRoot Object](../Topic/The-ObjectModelRoot-Object.md)
 Example: The root $psISE object.

 [The PowerShellTab Object](../Topic/The-PowerShellTab-Object.md)
 Examples: $psISE.CurrentPowerShellTab, $psISE.PowerShellTabs\[0\].

 [The PowerShellTabCollection Object](../Topic/The-PowerShellTabCollection-Object.md)
 Example: $psISE.PowerShellTabs.

## See Also
 [The Windows PowerShell ISE Scripting Object Model](../Topic/The-Windows-PowerShell-ISE-Scripting-Object-Model.md)

  