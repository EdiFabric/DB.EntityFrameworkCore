# EdiFabric C# .NET Examples for Entity Framework Core

## 1. Overview
EdiFabric is a software development kit for .NET Framework and .NET Core, which makes it straightforward to parse, generate, validate, acknowledge, split, customize, or in other words, to programmatically manipulate EDI files. It is written in C# and is distributed as a DLL file (a NuGet package is also provided) and C# files.  

It currently supports all message types for the X12, EDIFACT, HL7, and NCPDP EDI standards, the German automotive standard VDA, as well as custom formatted flat files (delimited, positional, or a mixture of both).  

> NOTE: EdiFabric does not provide any communication components (AS2 or SFTP, for example), has no dashboard or UI, and is not a full end-to-end EDI solution.
The best option to get the gist of what EdiFabric is, and can do, is to play around with the trial and examples.  

## 2. Requirements
- Visual Studio 2022.  
- Minimum .NET 6. 
- EdiFabric trial DLLs and serial number. 

## 3. Serial Key and EdiFabric trial DLLs
[Download the serial key](https://sowl.co/oApEt). The serial key is included in the file serial.key in folder edifabric-trial. Ensure it is there and that the file is not empty. The serial key is loaded in the file SerialKey.cs in project EdiFabric.Examples.X12.Common. Open the file and ensure that the serialKeyPath is correct. 
If the serial number is invalid or the file is missing, contact us at https://support.edifabric.com/hc/en-us/requests/new for assistance.  
The trial DLLs are in folders net45 (for .NET Framework 4.5+) and netcoreapp3.1 (for .NET Core 3.1+).

## 4. Entity Framework
All examples use Entity Framework Core 6.0.11. The supported Entity Framework Core versions are 3.x, 5.x, and 6.x. 

## 5. Getting started
Open Program.cs and follow the instructions there. The solutions contains 3 projects that use Entity Framework Core:

X12 4010 850  
X12 5010 837P (HIPAA)  
EDIFACT D96A ORDERS  

## 6. Trial use
The trial assemblies are valid for 14 days and are subject to EdiFabric's license terms available at https://www.edifabric.com/files/eula.pdf. Upon expiry, the trial DLLs will begin throwing exceptions.   
To continue using the trial and the examples, you'll need to request a trial extension.  

## 7. Warranty
*The source code in these example projects is strictly for demonstrational purposes and is provided "AS IS" without warranty of any kind, whether expressed or implied, including but not limited to the implied warranties of merchantability and/or fitness for a particular purpose.*

## 8. Additional information

[EdiFabric DB](https://support.edifabric.com/hc/en-us/articles/360029265372-EDI-to-DB)

[Install EdiFabric](https://support.edifabric.com/hc/en-us/articles/360016808578-Install-EdiFabric)

[Trial and Examples](https://support.edifabric.com/hc/en-us/articles/360000280532-Trial-and-Examples)

[EdiFabric Tutorial](https://support.edifabric.com/hc/en-us/articles/360000291511-Tutorial-EDI-NET-Tools-Basics)

[Knowledge Base](https://support.edifabric.com)

[Support](https://support.edifabric.com/hc/en-us/requests/new)

Last updated on November 22, 2022
### 2022 © EdiFabric
