# DiscSN
.NET 2.0 class library (based on code from the bizhawk team) that returns the game serial number from a PSX disc image (.cue or .ccd cuefile is required)

## Usage (C#):

* Add a reference to the DiscSN.dll
* string serial = DiscSN.SerialNumber.GetPSXSerial(@"\path\to\cue_or_ccd_file");

For safety, you should probably wrap the above in a try/catch block to handle any exceptions that may occur (the library hasnt been fully tested).

## Usage (VB):

* Add a reference to the DiscSN.dll
* Dim serial As String = DiscSN.SerialNumber.GetPSXSerial("\path\to\cueorccd")

For safety, you should probably wrap the above in a try/catch block to handle any exceptions that may occur (the library hasnt been fully tested).

## Attribution
This library uses code from BizHawk multi-system emulator - https://github.com/TASVideos/BizHawk
It also uses the LinqBridge assembly by Atif Aziz - https://www.nuget.org/packages/LinqBridge/1.3.0
