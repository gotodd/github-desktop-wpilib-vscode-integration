# github-desktop-wpilib-vscode-integration
Shows how to integrate the vscode that bundles with wpilib as your github desktop external editor

## The problem
Github Desktop on Windows allows you to link an external editor to open source files. However, it only recognizes the default installation of VSCode, and does not recognize the VSCode editor that comes with the [WPIlib](https://github.com/wpilibsuite/allwpilib/releases). Instead, it just shows `No external editors found`. 

## The solution
1. Download the file (github-wpilib-vscode-integration.reg)[https://raw.githubusercontent.com/gotodd/github-desktop-wpilib-vscode-integration/main/github-wpilib-vscode-integration.reg]. Right click -> Save As. 
2. Inspect it to make sure it contains no malicous content. Install it by double clicking on it.
3. Re-launch your Github Desktop application, and vscode should now show up in the File -> Opitons -> Integrations window. 
