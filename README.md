# Get_Next_Line

42 subject

First Circle

# what should we do?(どんな課題？)

Make file loading func.
If you want more infomation, then should be a 42 student.

# Directory Structure(ファイル構成)

```
Get_Next_Line
├── bonus
│  ├── get_next_line_bonus.c
│  ├── get_next_line_bonus.h
│  ├── get_next_line_utils_bonus.c
│  └── Makefile
├── mandatory
│  ├── get_next_line.c
│  ├── get_next_line.h
│  ├── get_next_line_utils.c
│  └── Makefile
└── README.md
```

# Status(課題の進捗)

🎉DONE!!!🥳🎉

[![hkikuchi's 42Project Score](https://badge42.herokuapp.com/api/project/hkikuchi/get_next_line)](https://github.com/JaeSeoKim/badge42)


# HOW TO MOVE IT?(ENGLISH)
日本語での使用方法の説明は[こちら](#%E3%81%A9%E3%81%86%E3%82%84%E3%81%A3%E3%81%A6%E5%8B%95%E3%81%8B%E3%81%99%E3%81%8B)



1. Git clone this repository to your rocal environment. (If you already git user and could reach here, then you know this command.)

```
git clone git@github.com:HinataKikuchi/Get_Next_Line.git
```

2. JUST DO MAKE.

```
$ cd ./Get_Next_Line
$ make -C ./mandatory
```

3. Archive file(named ```libft.a```) will appear in srcs, when successfully Compiled.

4. If you want to use libft funcs in your dir, examples bellow.

```
$ gcc -I./Get_Next_Line/mandatory -L./Get_Next_Line/mandatory -lgnl <your_source_name>
```

5. FIN.


# どうやって動かすか？

1. このレポジトリをクローンしてください。

```
git clone git@github.com:HinataKikuchi/Get_Next_Line.git
```

2. メイクしてもろて

```
$ cd ./Get_Next_Line
$ make -C ./mandatory
```

3. コンパイルに成功するとアーカイブファイル(```libft.a```って名前のやつ)がsrcs下にできます。

4. もしlibft内の関数を自分のファイルで使いたいときは以下の例のように使ってください。

```
$ gcc -I./Get_Next_Line/mandatory -L./Get_Next_Line/mandatory -lgnl <your_source_name>
```

5. おーわり！
