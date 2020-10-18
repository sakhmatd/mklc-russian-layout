# MKLC Russian Keyboard Layout

This is a hacky way to get a Russian (ЙЦУКЕН) keyboard layout in Windows when one is unwilling
or unable to install the entire ru-RU locale.

# Usage

Clone the repository (requires [Git for Windows](https://git-scm.com/download/win) 
or download it as a ZIP file using the green Code button above.

Open the `layout` folder and run `setup.exe`

It's that easy.

Russian will now appear in your list of available layouts.
Use the standard windows shortcuts (Win-SPACE, Alt-Shift, Ctrl-Shift) to change between layouts.

# Uninstalling

If you wish to uninstall the layout, navigate to 
`Control Panel\Programs\Programs and Features` (aka "Add or Remove Programs"), 
find `Russian (ЙЦУКЕН)` in the list and hit `Uninstall` in the top panel.

# Changing the layout

The layout was made with [MKLC](https://www.microsoft.com/en-us/download/details.aspx?id=102134),
so you will need to download and install it to make any changes to the keyboard.

Some people may wish to change the default locale from en-US to something else, for example.

Find the source file in the `src` directory of this repository and open it with MKLC to make any changes.

# License

Whatever doesn't automatically belong to Microsoft is licensed under Apache 2.0. You can locate the terms of that license in
the `LICENSE` file.