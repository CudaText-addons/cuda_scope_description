plugin for CudaText.
shows signature of each function below the end of the function.
e.g. after closing bracket of the function "main" it shows text like this:
  "// end of int main(int argc, char *argv[])"

works for C and C++ lexers. list of lexers is configurable so you can add other C-like lexers.
must be activated via menu item in the "Plugins / Scope Description" menu: "Toggle ON/OFF"

supports 2 modes of display:
a) mode "using gaps" - shows signature in the inter-line gap.
   it may/will conflict with few other CudaText plugins which use gaps: Differ, Insert Pics.
b) mode "without gaps" - shows colored rectangle with text in the ending line.
mode can be changed using menu item in the "Plugins / Scope Description".


author: Yuriy Balyuk, https://github.com/veksha
micro changes: Alexey Torgashin (CudaText)
license: MIT
