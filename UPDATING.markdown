# Deploying Changes

    git checkout source
    git push origin source

    rake setup_github_pages
    rake generate
    rake deploy

# Updating Octopress

    git remote add octopress https://github.com/imathis/octopress.git
    
    git checkout source
    git pull octopress master
    bundle install
    rake update
    git status
    git push origin source
