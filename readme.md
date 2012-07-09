
# Preparation
mkdir ~/bin

PATH=~/bin:$PATH

curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/bin/repo

chmod a+x ~/bin/repo

repo init -u git://github.com/isapoetra/cgaf-repo.git
