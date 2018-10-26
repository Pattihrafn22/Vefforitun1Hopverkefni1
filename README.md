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

Sass skrár eru í möppu: scss, fyrir utan styles.scss sem er í aðalmöppu.  styles.scss kallar á import fyrir hinar skrárnar.  Í heildina eru 8 sass skrár: styles.scss, index.scss, products.scss, staff.scss, cart.scss, config.scss, header.scss og footer.scss.  
Í config eru fastar og grunnskilgreiningar sem gilda fyrir allar síður.

Í json skrá er sett upp: Browsersync, sass, sass-watch, lint-scss og npm-run-all. 

Höfundar verkefnis eru:  
* Freyja Sigurgísladóttir     - frs24@hi.is
* Patrekur Hrafn Hallgrímsson - phh4@hi.is
