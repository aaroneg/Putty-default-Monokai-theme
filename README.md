# MonokaiDefaultTheme.reg
Allows you to use the monokai theme as default

# MonokaiSession.reg
Creates a "Monokai" session in putty that you can load, add a hostname to, etc, and save as a server name if you only want to use monokai for _some_ servers

# PuTTY Monokai Default Theme.msi
User-only MSI to apply monokai as default. You can use this to deploy the change through SCCM as required or optional. Must be advertised to the user because it is not a machine-level installer.

# PuTTY Monokai Default Theme.aip
Source file for the MSI. Use advanced installer to open it if you'd like to build/change the MSI yourself, or validate that the MSI contains nothing sneaky by building a new MSI for yourself.

# Subfolders
included because that's the folder the AIP is configured to place the newly-built MSI in.
