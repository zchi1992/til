# Homebrew

## How to config homebrew to use 国内镜像
Add below environment variables to the `~/bashrc` file to use Tsinghua mirrow  
`export HOMEBREW_BREW_GIT_REMOTE="https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/brew.git"  
export HOMEBREW_CORE_GIT_REMOTE="https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-core.git"`  
make sure you disable `http.proxy` and `https.proxy` in git global config file `.gitconfig`.  
if they are set in the `gitconfig` file. Then don't set mirrow.  
