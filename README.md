# BlobBUDDY Installer
This is the source file for the BlobBUDDY Installation script, that can freely be used for any other Microsoft Agent program.

# Compile Instructions
1. Download NSIS 2.51
2. Modify the script as needed for your program
3. Inside the software, click "Compile NSI scripts"
4. Drag your script in and try it out!

# Why does this exist?
Recently, Microsoft Agent software has been plagued with false positives from vendors, specifically with installer files since the majority of installers install another program (Microsoft Agent itself) when running. This script is intended to help mitigate this by showing what actually goes on during the full installation process, and thus reduce the amount of false positives.
