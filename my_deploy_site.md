### Wiki to update and deploy site

**To deploy the site locally:**

- Update baseurl in the config file  
> config/_default/config.toml
> baseurl = "/"

- In command prompt go the website folder and run hugo server
> ...\Github\My_New_Website> hugo server

- View the site at http://localhost:1313/

**To deploy the site on github server:**

- Update baseurl in the config file  
> config/_default/config.toml
> baseurl = "https://divyashah.github.io/"

- In command prompt go to website folder and run hugo to generate the site
> ...\Github\My_New_Website> hugo

- Copy site data from public folder to your host repository
> ..\Github\My_New_Website\public

- View the site at https://divyashah.github.io/
