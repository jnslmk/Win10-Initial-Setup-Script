# Manual Changes
This file specifies changes need to be applied manually, because it is not 
possible or not yet implemented to apply them automatically.

## Set Display Scale to 100%
Right click on desktop, select *Display settings* and select *100%* under *Scale 
and Layout*. 

It is difficult to apply these changes automatically, because the 
registry values to be set depend on the default scaling determined by Windows 
which depend on monitor size and resolution. It would be possible to calculate 
the windows defaults and apply values accordingly.

## Change Powershell Color Scheme
The setup script by default install the colortool command line program. Execute 
`colortool solarized_dark` in powershell to apply the color scheme to the 
current powershell window. Now right click on powershell windows, select 
*properties* and click *OK*.

It might be possible to apply these changes automatically by checking if 
registry values are being modified by applying these changes manually.