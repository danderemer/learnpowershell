# Learn PowerShell in a Month of Lunches by Don Jones and Jeffrey Hicks

Started February 19th, 2018 - Dan DeRemer

## Preface

I am learning PowerShell to assist with my day-to-day tasks working with Microsoft products, specifically Microsoft Azure. The intended goal after completing this book is to be able to better write PowerShell scripts that can function at a higher level than just sequentially executing cmdlets.

## About

I will be using Visual Studio Code (VSCode) with the PowerShell plugin. I have set up a project directory on my machine under my user profile's documents directory to store my notes and exercises. I can easily switch between coding and writing notes using the tabbed layout of VSCode. I can also execute PowerShell scripts within VSCode using the Terminal function  ( CTRL + \` ).

### PowerShell Setup Notes

I set up PowerShell a bit differently than the book suggested. Here are the things I did differently:

* Activated `Enable line wrapping selection`
* Set `Buffer Size` to 999 and `Number of Buffers` to 8.
* Set the `Height` value to 3000 under `Screen Buffer Size` in layout tab and make sure both `Width` values are set to 120 for both `Screen Buffer Size` and `Window Size`.
* Installed [Hack](https://github.com/source-foundry/Hack) font using [Chocolatey](https://chocolatey.org/install) to install the `hackfont` package. Instructions are as follows:

  * Install Chocolatey

  ```PowerShell
  Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
  ```

  * Install Hack font

  ```PowerShell
  choco install hackfont
  ```

  * Set PowerShell font to Hack font and increase size to 16.