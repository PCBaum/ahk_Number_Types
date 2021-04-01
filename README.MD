## Autohotkey for ℝℤℂℚ

This AHK script lets you easily access commonly used Symbols for the different Number Types (Real, Complex, Rational, and Integer)

Either use \\R with the usual Letter, or use \real with the firest 3-4 letters of the name (normally case sensitive, but in the script there are options for both uncapitalized "real", and capitalized "Real")

```
\\R → ℝ , \real → ℝ, or \Real → ℝ

```
## AHK Installation

  1. Download [Autohotkey](https://www.autohotkey.com/download/) and install it. 
  2. Download the [script ℝℤℂℚ.ahk](https://github.com/PCBaum/ahk_Number_Types/blob/main/%E2%84%9D%E2%84%A4%E2%84%82%E2%84%9A.ahk)
   or create a new script with your prefered Name and copy paste the Key Mapping into it.
  3. Put the script into a folder of your choice. 
  4. Start the script Greek_Alphabet.ahk 
  
  Optional: 
  
  5. Compile your Script with rightclick → compile script (shoud be somewhere around the the second row)
  
  6. Put the executable ("YOUR_SCRIPT_NAME".exe) in your Startup Folder "C:\Users\"USERNAME"\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup" to have the script automatically start on Startup.
  
  
# Whithout installing AHK on Windows

  1. Download the compiled [ℝℤℂℚ.exe](https://github.com/PCBaum/ahk_Number_Types/blob/main/%E2%84%9D%E2%84%A4%E2%84%82%E2%84%9A.exe) File
  2. Put the script into a folder of your choice.
  3. Start the script Greek_Alphabet.exe
  
  Optional:
  
  4.  Put the executable in your Startup Folder "C:\Users\"USERNAME"\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup" to have the script automatically start on Startup.

## Key Mapping 

how this AHK script maps input to output: 
::input::output   output is given as the Unicode code.

```

#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.
#Hotstring C * ?
::\\R::{U+211D}
::\\Q::{U+211A}
::\\Z::{U+2124}
::\\N::{U+2115}
::\\C::{U+2102}
::\real::{U+211D}
::\rat::{U+211A}
::\ganz::{U+2124}
::\int::{U+2124}
::\nat::{U+2115}
::\com::{U+2102}
::\Real::{U+211D}
::\Rat::{U+211A}
::\Int::{U+2124}
::\Ganz::{U+2124}
::\Nat::{U+2115}
::\Com::{U+2102}
#Hotstring *0 ?0 C0

```

## Credits

Template for AHK Script: was a some time ago and I don't remember. Also, the beginning seems to be standard, and is the only not heavily changed part.
