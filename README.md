# How to decompile Java

This work is devoted to God.

```
"C:/Program Files/JetBrains/IntelliJ IDEA Community Edition 2021.3/jbr/bin/java.exe" -cp "C:/Program Files/JetBrains/IntelliJ IDEA Community Edition 2021.3/plugins/java-decompiler/lib/java-decompiler.jar" org.jetbrains.java.decompiler.main.decompiler.ConsoleDecompiler -hdc=0 -dgs=1 -rsy=1 -rbr=1 -lit=1 -nls=1 -mpm=60 "<PATH_TO_JAR_TO_DECOMPILE>" "<DECOMPILIATION_OUTPUT_PATH>"
```

This creates a `.jar` file at the output path with the source code in it. It can be unarchived with 7-Zip.
