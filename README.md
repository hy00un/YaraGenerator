## YaraGenerator (IDA Plugin)

YaraGenerator is a tool to help you make yara rule in IDA.

If you enter an address, the assembly of that address is created as a Yara rule.

Complete automation is due to the existence of false positives.

The wildcard feature is currently under study.

### [ YaraGenerator ]
<img src="images/YaraGenerator.png" width="100%">

### [ YaraChecker ]
<img src="images/YaraChecker_1.png" width="100%">
<img src="images/YaraChecker_2.png" width="100%">

### [ YaraIcon ]
<img src="images/YaraIcon.png" width="100%">

### Install & Tutorial

pip install yara-python

pip install capstone

pip install keystone-engine

pip install pefile

pip install pillow

copy YaraGenerator.py C:\Program Files\IDA 7.0\plugins

copy assembler_disassembler.py C:\Program Files\IDA 7.0\plugins

YaraGenerator HOT-KEY : Ctrl + Shift + Y

assembler_disassembler HOT-KEY: Ctrl + Shift + A

