# Betty
Utility tool for making backups of databases, files and directories directly to Google Drive. With combination of Cron it becomes a powerful and free backup solution.

### Tech
   
* [Bash] - script language
* [gdrive] - shell tool for communication with Google Drive
* [Google Drive] - backups storage

### Prerequisites

Install and configure `gdrive` tool: [Download](https://github.com/prasmussen/gdrive)

### Usage

1. Create configuration file (see 'example.cfg' file).
2. Run backup process:
```sh
$ ./bin/betty example.cfg
```

License
----

GPL-3.0


**Free Software, Hell Yeah!**

[//]:#


   [Bash]: <https://www.gnu.org/software/bash/>
   [gdrive]: <https://github.com/prasmussen/gdrive>
   [Google Drive]: <https://www.google.com/drive>


