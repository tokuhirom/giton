# SYNOPSIS

    > giton install
    Install modules.

    > giton check
    Checking, modules are installed.

# Format of giton.json

    {
        "dependencies":[
            {
                "repository":"git@github.com/tokuhirom/JKML.git',
                "ref":"0.01",
            },
        ]
    }

giton.json をよんで、local/ にインストールする。

local/.giton.installed.json に、インストールしたもののリストが記録される。

\`giton check\` で、指定されてるものがすべてはいってるかチェックできる。

    > giton install --local local/

のようにして、パスを指定可能。

# POD ERRORS

Hey! __The above document had some coding errors, which are explained below:__

- Around line 189:

    Non-ASCII character seen before =encoding in 'をよんで、local/'. Assuming UTF-8
