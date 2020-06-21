Repo Steps : 
A. Install Hugo : https://gohugo.io/getting-started/installing/
B. Clone Repo -> cd into repo
C. run : hugo server -D


All Basic Steps :
1. Install Hugo : https://gohugo.io/getting-started/installing/
2. Verify installation : hugo version
3. Create new site : hugo new site quickstart
4. Add a theme : cd quickstart
                git init
                git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
5. add theme to site config : echo 'theme = "ananke"' >> config.toml
6. create first post : hugo new posts/my-first-post.md
7. start server : hugo server -D