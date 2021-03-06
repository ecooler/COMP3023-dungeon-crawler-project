## Assignment 1 Dungeon Crawler

This is the provided Qt Creator for the the Dungeon Crawler assignment
for the course COMP3023 Software Development with C++.

Please familiarise yourself the content of this project. Also, do not
forget to initialise a git repository in this folder once you have
extracted the folder to your filesystem.

First thing you will need to do is modify the main.cpp file to include
your name (the author) and the name you would like to call the game.
You may call your game whatever you like.

In this project, all of the class declarations have been provided for
you, except for any additional classes you thought necesayr to include
in your design. You will need to complete the classes with the correct
inheritance, data members, member functions, etc.

Some classes already come with some provided code and/or suggested
interfaces. Code that MUST NOT be changed is clearly marked, while
code that you are allowed to change is clearly marked that you are
allowed to or may need to modify it, as some of the provided
examples do not conform to what you need to end up implementing.

Please read the comments in the files, particularly those with
provided implementations as they will tell you what the code is for.

To reduce the number of files included in the project, some of the
classes have been grouped together. For example, all weapons and
enchantment related classes are included in weapons.h and weapons.cpp.

The following is a brief list of the files included in this project and
their purpose:

- basicdungeon.h/.cpp: header and implementation file for concrete classes
                       related to the Basic Dungeon type.
- character.h/.cpp: header and implementation file for the Character class
- commondungeon.h/.cpp: header and implementation file for concrete classes
                        common to both dungeon types, e.g., OpenDoorway
- creatures.h/.cpp: header and implementation file for the Creature class
- creature_types.csv: a CSV file containing the three original creature types;
                      this is the file you will load when you instantiate your
                      creature prototypes from the data file.
- creature_types_sample.csv: a CSV file used by the CsvFile Unit Tests; DO NOT MODIFY
- csvfile.h/.cpp: header and implementation file for the CsvFile class
- door.h/.cpp: header and implementation file for the abstract Door class
- dungeon.h/.cpp: header and implementation file for the abstract Dungeon class
- game.h/.cpp: header and implementation file for the Game class; includes
               a suggested interface, but can be changed. Implemented helper
               functions must not be changed.
- magicaldungeon.h/.cpp: header and implementation file for concrete classes
                         related to the Magical Dungeon type.
- main.cpp: implementation only, includes the main function
- menuinterface.h/.cpp: header and implementation file for the MenuInterface
                        class; fundamentals are implemented, menus and processing
                        must be completed by you to fulfill the assignment specs.
- room.h/.cpp: header and implementation file for the abstract Room class
- testing.h/.cpp: header and implementation file for the simple Unit Testing
                  framework. Includes complete tests for CsvFile, you should
                  implement additional tests for your own work.
- testingsettings.h: header only, includes some macro defintions to enable/disable testing
- wall.h/.cpp: header and implementation file for the abstract Wall class
- weapons.h/.cpp: header and implementation file for the weapon related classes,
                  such as, Weapon, Fists, Enchantment, FlamingEnchantment, etc.
# COMP3023 dungeon crawler project
# ????????? powcoder

# [????????????CS???????????????????????????](https://powcoder.com/)

[????????????](https://powcoder.com/tag/????????????/)

[java??????](https://powcoder.com/tag/java/) [c/c++??????](https://powcoder.com/tag/c/) [python??????](https://powcoder.com/tag/python/) [drracket??????](https://powcoder.com/tag/drracket/) [MIPS????????????](https://powcoder.com/tag/MIPS/) [matlab??????](https://powcoder.com/tag/matlab/) [R????????????](https://powcoder.com/tag/r/) [javascript??????](https://powcoder.com/tag/javascript/)

[prolog??????](https://powcoder.com/tag/prolog/) [haskell??????](https://powcoder.com/tag/haskell/) [processing??????](https://powcoder.com/tag/processing/) [ruby??????](https://powcoder.com/tag/ruby/) [scheme??????](https://powcoder.com/tag/drracket/) [ocaml??????](https://powcoder.com/tag/ocaml/) [lisp??????](https://powcoder.com/tag/lisp/)

- [?????????????????? data structure algorithm ??????](https://powcoder.com/category/data-structure-algorithm/)
- [??????????????? ??????????????? computer network socket programming ??????](https://powcoder.com/category/network-socket/)
- [????????? DB Database SQL ??????](https://powcoder.com/category/database-db-sql/)
- [???????????? machine learning ??????](https://powcoder.com/category/machine-learning/)
- [??????????????? Compiler ??????](https://powcoder.com/category/compiler/)
- [????????????OS(Operating System) ??????](https://powcoder.com/category/????????????osoperating-system/)
- [?????????????????? Computer Graphics opengl webgl ??????](https://powcoder.com/category/computer-graphics-opengl-webgl/)
- [???????????? AI Artificial Intelligence ??????](https://powcoder.com/category/????????????-ai-artificial-intelligence/)
- [????????? Hadoop Map Reduce Spark HBase ??????](https://powcoder.com/category/hadoop-map-reduce-spark-hbase/)
- [???????????? System programming ??????](https://powcoder.com/category/sys-programming/)
- [???????????? Web Application ??????](https://powcoder.com/category/web/)
- [?????????????????? NLP natural language processing ??????](https://powcoder.com/category/nlp/)
- [????????????????????? Computer Architecture ??????](https://powcoder.com/category/computer-architecture/)
- [????????????????????????computer security cryptography ??????](https://powcoder.com/category/computer-security/)
- [??????????????? Computation Theory ??????](https://powcoder.com/category/computation-theory/)
- [???????????????(Compute Vision) ??????](https://powcoder.com/category/???????????????compute-vision/)

