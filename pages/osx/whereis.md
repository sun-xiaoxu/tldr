# whereis

> 查找二进制文件位置

- 查找ssh.sh位置:

`whereis {{ssh}}`

- Locate binary and man pages for ls:

`whereis -bm {{ls}}`

- Locate source of gcc and man pages for git:

`whereis -s {{gcc}} -m {{git}}`

- Locate binaries for gcc in /usr/bin/ only:

`whereis -b -B {{/usr/bin/}} -f {{gcc}}`
