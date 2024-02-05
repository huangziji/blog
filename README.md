    hugo new site huangziji

    cd huangziji/themes

    git clone https://github.com/janraasch/hugo-bearblog

    cd ..

    hugo new posts/post.md

    hugo server

    git submodule add -b main https://github.com/huangziji/huangziji.github.io.git public

    hugo -t hugo-bearblog