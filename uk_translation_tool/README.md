#### NOTE:
- All the commands should be run from the projects root directory
- add -j{n} flag to your make command to make use of all the CPU (where {n} is the number of threads, usually equals to the number of cpu cores)

### To update font textures
```bash
$ cd uk_translation_tool
$ ./copy_font_textures.sh
```


### To build ROM with ukrainian translation, run:
```bash
$ make VERSION=jp LANG_PATCH=uk COMPARE=0
```

### To update textures & build
```bash
$ cd uk_translation_tool/ && ./copy_font_textures.sh && cd .. && make VERSION=jp LANG_PATCH=uk  COMPARE=0
```