# hugo-satrdays-theme

## About
This is a theme repository for satRday conference websites using the hugo static site generator. It is designed to be used in tandem with `hugo-agency-theme` a [theme by digitalcraftsmen](https://github.com/digitalcraftsman/hugo-agency-theme). 

## Usage

1. Install `hugo`
    * [Install Hugo](https://gohugo.io/getting-started/installing/)
2. Start a new site
    ```
    hugo new site [city][year] # such as cardiff2018
    
    cd [city][year]
    
    git init
    ```
3. Install `hugo-agency-theme` as a submodule
    ```
    git submodule add https://github.com/digitalcraftsman/hugo-agency-theme themes/hugo-agency-theme
    ```
4. Install `hugo-satrday-theme` as a submodule
    ```
    git submodule add https://github.com/satRdays/hugo-satrdays-theme themes/hugo-satrdays-theme
    ```
5. copy the `config.toml` [from thie site](https://github.com/satRdays/satRday_site_template/blob/master/config.toml) into your projects root (i.e. `/cardiff2018/config.toml`)

6. copy the files in `hugo-satrdays-theme/data/projects/` into `[city][year]/data/projects/` e.g. `/cardiff2018/data/projects/`

7. check if the site builds
   ```
   hugo serve
   ```
   go to the port listed in the return to see your site e.g. `localhost:xxxx`, probably `localhost:1313`
   
8. modify the params in the `config.toml` 
