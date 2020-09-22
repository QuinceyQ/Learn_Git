GIT相关指令

1.git 配置
    git config --global user.name // user.email // core.editor "xxx"s
    git config --list

2.git 基本命令
    git init

    git status
    
    git add
    
    git commit
        git commit -a -m "description"
    
    git restore --staged xxx
        # git restore --staged readme.md
    
    git log
    
    git checkout xxxxxxx/master 
        # git checkout e8befcd
        # git checkout "tag"/v1.0 


    git diff 'xxxxxxx' 'filename'
        # git diff e8befcd .\readme.md

    git clone xxxxxxx

    git push/pull

    git tag xxx
        # git tag v1.0
        # git tag v0.9 ebd67cf

    


