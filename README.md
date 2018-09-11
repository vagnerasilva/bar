# teste
[core]
        repositoryformatversion = 0
        filemode = true
        bare = false
        logallrefupdates = true
        ignorecase = true
        precomposeunicode = false
[branch "master"]
        remote = bar
        merge = refs/heads/master
[remote "bar"]
        url = https://github.com/vagnerasilva/bar.git
        fetch = +refs/heads/*:refs/remotes/bar/*
[remote "foo"]
        url = https://github.com/vagnerasilva/foo.git
        fetch = +refs/heads/*:refs/remotes/foo/*
[remote "all"]
        url = https://github.com/vagnerasilva/foo.git
        fetch = +refs/heads/*:refs/remotes/all/*
        pushurl = https://github.com/vagnerasilva/foo.git
        pushurl = https://github.com/vagnerasilva/bar.git

        #### aqui 