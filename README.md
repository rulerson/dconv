# dconv
Convert encoding of all text files under directory recursively, in place. A simple shell script, no special denpendency except of iconv utility.

# Usage
Usage: dconv <target-dir> [<from-encoding default=gbk>] [<to-encoding default=utf8>]
 
Convert encoding of all text files under <target-dir> from <from-encoding> to <to-encoding>, in place, recursively.
Text file determined by following suffix: .cpp/.c/.h/.xml/.txt, you can add your choice simply by edit shell code.
Dconv will bankup <target-dir> beside before convertion start.
