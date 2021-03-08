#### TO DOs
- [ ] **update the template/theme files**
- [ ] **add more details on the current phd project**
- [ ] **consider adding transcripts to download**

- [ ] for all the download link boxes (poster, slide, pdf, web, etc), add some icons there ...
- [ ] also ensure correct name for each of the links ...
- [ ] create a short bio with links for all the author pages, at least main ones like AP, GM, SC, YJK, YW ...  

- [ ] Add the skills widget on the home page
- [ ] Add `Web` shortcut box for the `Conferences & Schools` section
- [ ] Add *IEEE/ASME AIM 2020* page under `Conferences & Schools` section
- [ ] Consider adding filter in `Conferences & Schools` section like in the `Publications` widget

- [ ] add project about robocon
- [ ] add master/graduate course projects
- [ ] see if you can `justify` align the text  
- [ ] consider adding a cover pic or a header image  

- [ ] Image zoom-in on featured publications
- [ ] add *CV* as a media link in the main bio under profile pic or add a download emoji in text
- [ ] add supervisors on project page in the form of bio cards like in [research group theme](https://research-group.netlify.app/people/)
- [ ] add your career goals
- [ ] **add a motivational statement/page/blog**

- [ ] update bios and add motivation for robotics
- [ ] improve/organize tags
- [ ] consider adding quotes/phrases
- [ ] consider all social media links

- [ ] add "Hobbies" section of some other relevant but informal/ extra curricular section showing details or maybe a short description with a `Gallery` about lindy hop, hiking, travelling
- [ ] check how 2nd 3rd generation menus (sub-menus) work ...
- [ ] discover how to add analytics to the site
- [ ] do the search engine optimization
- [ ] improve and update the what's new section ...
- [ ] if you manage to write down a few lines for the events experienced, then it can be turned into a `Recent Posts` section which can also become your what's new

- [ ] consider adding the site in italian or other languages

- [x] Quickly discover relevant content by filtering publications.
- [x] download links in the description of each project are not correct
- [x] add a cv section or pdf
- [x] add bachelor thesis project
- [x] Add "Events" section list all the conferences and schools attended
- [x] gives slides, talks, posters for download here ...
- [x] remove the "Posts" section and put details of summer school in "Events" and period abroad within the project pages respectively

https://townsendcenter.berkeley.edu/blog/personal-academic-webpages-how-tos-and-tips-better-site

---

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
