```bash
"newest_file=$(ls -t | head -n1) && echo -e '--> Newest file:\\e[0;31m' $newest_file '\\e[0m'; [[ ! -f $fileNameWithoutExt.class || $newest_file != $fileNameWithoutExt.class ]] && echo '--> Compiling' $fileName'...' && javac $fileName; [[ -f $fileNameWithoutExt.class ]] && grep 'public static void main' $fileName > /dev/null 2>&1 && echo '--> Running...' && java $fileNameWithoutExt"
```

## Referências

* <https://stackoverflow.com/questions/5947742/how-to-change-the-output-color-of-echo-in-linux>

&nbsp;
