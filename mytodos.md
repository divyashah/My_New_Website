#### TO DOs

- [ ] **add more details on the current phd project**

- [ ] for all the download link boxes (poster, slide, pdf, web, etc), add some icons there ...
- [ ] also ensure correct name for each of the links ...
- [ ] create a short bio with links for all the author pages, at least main ones like AP, GM, SC, YJK, YW ...  

- [ ] add project about robocon
- [ ] add master/graduate course projects

- [ ] update bios and add motivation for robotics
- [ ] improve/organize tags

- [ ] add "Hobbies" section of some other relevant but informal/ extra curricular section showing details or maybe a short description with a gallery about lindy hop, hiking, travelling
- [ ] check how 2nd 3rd generation menus (sub-menus) work ...
- [ ] discover how to add analytics to the site
- [ ] improve and update the what's new section ...

- [ ] consider adding the site in italian or other languages

- [x] add a cv section or pdf
- [x] add bachelor thesis project
- [x] Add "Events" section list all the conferences and schools attended
- [x] gives slides, talks, posters for download here ...
- [x] remove the "Posts" section and put details of summer school in "Events" and period abroad within the project pages respectively

---

### Wiki to update and deploy site

**To deploy the site locally:**

- Update baseurl in the config file  
> config/_default/config.toml
> baseurl = "/"

- In command prompt go the website folder and hugo server
> ...\Github\My_New_Website> hugo server

- View the site at http://localhost:1313/

**To deploy the site on github server:**

- Update baseurl in the config file  
> config/_default/config.toml
> baseurl = "https://divyashah.github.io/"

- In command prompt go to website folder and run hugo to generate the site

- Copy site data from public folder to your host repository
> ..\Github\My_New_Website\public

- View the site at https://divyashah.github.io/
