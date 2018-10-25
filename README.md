# HOW TO 

Til að keyra: 
```bash
npm install
npm run dev
````

Til að keyra stylelint: 
```bash
npm run lint-scss
```

Allar HTML skrár eru í möpppu: pages, fyrir utan index sem er í aðalmöppu.
HTML skrár eru fjórar talsins, þ.e. index.html, products.html, staff.html og cart.html

Sass skrár eru í möppu: scss, fyrir utan styles.scss sem er í aðalmöppu.  styles.scss kallar á import fyrir hinar skránar.  Í heildina eru 5 sass skrár: styles.scss, index.scss, products.scss, staff.scss, cart.scss og config.scss.  
Í config eru fastar og grunnskilgreiningar sem gilda fyrir allar síður.

Í json skrá er sett upp: Browsersync, sass, sass-watch, lint-scss og npm-run-all. 

Höfundar verkefnis eru:  
* Patrekur Hrafn Hallgrímsson - phh4@hi.is
* Freyja Sigurgísladóttir     - frs24@hi.is
* Mimoza Herta Róbertsdóttir  - mhr4@hi.is
