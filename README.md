# DiscSN
.NET 2.0 & 4.5.2 class libraries (based on code from the bizhawk team) that returns the game serial number from a PSX disc image (.cue or .ccd cuefile is required)

See releases page for the latest compiled DLLs: https://github.com/Asnivor/DiscSN/releases/latest

## Usage (C#):

* Add a reference to the DiscSN.dll
* string serial = DiscSN.SerialNumber.GetPSXSerial(@"\path\to\cue_or_ccd_file");

For safety, you should probably wrap the above in a try/catch block to handle any exceptions that may occur (the library hasnt been fully tested).

## Usage (VB):

* Add a reference to the DiscSN.dll
* Dim serial As String = DiscSN.SerialNumber.GetPSXSerial("\path\to\cue_or_ccd_file")

For safety, you should probably wrap the above in a try/catch block to handle any exceptions that may occur (the library hasnt been fully tested).

## Attribution
This library uses code from BizHawk multi-system emulator - https://github.com/TASVideos/BizHawk

The .NET 2.0 version also uses the LinqBridge assembly by Atif Aziz - https://www.nuget.org/packages/LinqBridge/1.3.0
