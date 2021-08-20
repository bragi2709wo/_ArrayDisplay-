# _ArrayDisplay-
1st _ArrayDisplay shows $GROUP[0][0] = 3
#include <Array.au3>

GLOBAL $GROUP = INIReadSection(@ScriptDir & "\config.ini", "GROUP")
_ArrayDisplay($GROUP)

_ArrayAdd($GROUP, "X|")
_ArrayAdd($GROUP, "Y|")
_ArrayDisplay($GROUP)
