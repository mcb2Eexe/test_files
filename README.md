# test_files

Repo of test files which can be used to trigger detections

# vbs_macro

Microsoft Office Excel document with embedded macro to execute calc.exe using VBScript

Process tree:

Excel.exe > wscript.exe > cmd.exe

Usage:

Drop excel doc and vbs script in location of choice, open excel doc and enable content

# jar_exe

JAR file designed to execute calc.exe when opened

Process tree:

cmd.exe > java.exe > calc.exe

Usage:

Drop in location of choice and execute using cmd: java -jar test.jar

# powershell

Clean PS script for testing remote PS downloads
