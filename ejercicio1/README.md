
C:\Users\Leandro\Desktop\cmder
λ pwd
C:\Users\Leandro\Desktop\cmder

C:\Users\Leandro\Desktop\cmder
λ mkdir ejercicios
Ya existe el subdirectorio o el archivo ejercicios.

C:\Users\Leandro\Desktop\cmder
λ code
                                                                            C:\Users\Leandro\Desktop\cmder
λ code .
                                                                            C:\Users\Leandro\Desktop\cmder
λ cd ejercicios
                                                                            C:\Users\Leandro\Desktop\cmder\ejercicios (main -> origin)
λ cd ejercicio 1
El sistema no puede encontrar la ruta especificada.

C:\Users\Leandro\Desktop\cmder\ejercicios (main -> origin)
λ cd ejercicio1
                                                                            C:\Users\Leandro\Desktop\cmder\ejercicios\ejercicio1 (main -> origin)
λ touch README.md
                                                                            C:\Users\Leandro\Desktop\cmder\ejercicios\ejercicio1 (main -> origin)
λ git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


C:\Users\Leandro\Desktop\cmder\ejercicios\ejercicio1 (main -> origin)
λ git config --global user.name Leandro Osorio
                                                                            C:\Users\Leandro\Desktop\cmder\ejercicios\ejercicio1 (main -> origin)
λ git config --global usar.mail leandroosorio23@hotmail.com
                                                                            C:\Users\Leandro\Desktop\cmder\ejercicios\ejercicio1 (main -> origin)
λ ..
                                                                            C:\Users\Leandro\Desktop\cmder\ejercicios (main -> origin)
λ git init
Reinitialized existing Git repository in C:/Users/Leandro/Desktop/cmder/ejercicios/.git/

C:\Users\Leandro\Desktop\cmder\ejercicios (main -> origin)
λ git commit -m "version inicial"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    README.md
        deleted:    ejercicios1/README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicio1/

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Leandro\Desktop\cmder\ejercicios (main -> origin)