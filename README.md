<article class="markdown-body entry-content" itemprop="mainContentOfPage">

![Diamonds Logo](http://cinemacloud.co/diamondstack.png?58)

**Diamonds** is an isomorphic fullstack seed with generators for Angular & Polymer +Express distributed web & native applications delivering **hexagonal microservices** as components and elements. Imported popular packages are SNS, E-Commerce, and Mail-Messaging APIs servicing Polymer+Angular clientele on web, mobile, or native devices.

##### **Generators**
![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `$> ./d.js (c|r|u|d) [type] Element_Name(+pattern)`<br><br>
[![](http://cinemacloud.co/cloud_facets.png?.52)](#)

##### **Faceting**
![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `$> pm2 start d.js -i 3 --name <APPNAME>`<br><br>
Facets are public at http://&lt;n_facet_host&gt;:8080/ once above command runs pm2 cluster profile.
<br><br>
On creation "facets" gen SSH keys within your Diamond cluster so apps can share code & data as if a unified app & fs.

##### **Browser Model & Code Editing**
**Model:** Compose relational data model with *wwwsqldesigner* allowing visually scoring of model.<br>
**Control:** Live edit elements+components in NoIDE's *Ace* supporting livereload and browsersync.
<br>GAnalytics, Stripe, and social network oauth configs are here as well.
URL: http://&lt;n_facet_host&gt;:8080/edit
<br><br>
##### **Performance Monitors**
View Prometheus-Grafana performance data for each facet (aka Diamond server) at
URL: http://&lt;n_facet_host&gt;:8080/perf

##### **PolyBuild, Closure Compiler, and Deploy**

| <img src=http://cinemacloud.co/stamp.png width=72 height=72> | <img src=http://cinemacloud.co/closure.png width=72 height=72> | <img src=http://cinemacloud.co/deploy.png width=72 height=72> |
| --- | --- | --- |
| WebComponent build tool | Angular's Production ES Optimizer| PM2 Deployment |

##### **Deploy Desktop, Device, & Mobile**

![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `$> d.js deploy [ web:default | all | mobile | desktop | device ];` // Performs Web, Ionic, & Electron build targets;

##### NPM Dependencies
<sup>
angular<Br>
angular-cli<br>
angular-seed<br>
 angular-seed-advanced<br>
polymer-cli<br>
closure-compiler<br>
electron, ionic<br>
browsersync<br>
generator-polymer<br>
express-ratelimit<br>
express-validation<br>
lovepouch = lovefield (sql) + pouchdb (kv)<br>
bluebird<br>
grunt-ts<br>
yarn<br>
pm2<br>
web-component-tester.</sup>

##### [<span class="octicon octicon-link"></span>](#source-projects)Source Projects
<sub>[Hex Architecture](http://victorsavkin.com/post/42542190528/hexagonal-architecture-for-rails-developers)</sub><br><br>
UI Tools<br>
<sub>[Angular](/tachy0n/diamonds/blob/master/angularjs.org)</sub><br>
<sub>[Polymer](/tachy0n/diamonds/blob/master/www.polymer-project.org) [1.0 Element Catalog](https://elements.polymer-project.org/)</sub><br>
<sub>[Polymer Designer](http://polymer-designer.appspot.com)</sub><br>
<sub>[Passport](/tachy0n/diamonds/blob/master/passportjs.org)</sub><br>
<sub>Material Design: [Polymer](https://www.polymer-project.org/docs/elements/material.html), [Angular](https://material.angularjs.org/), [Intro](http://www.google.com/design/spec/material-design/introduction.html)</sub><br>

Optmizations<br>
<sub>[Closure Compiler](https://github.com/google/closure-compiler)</sub><br>
<sub>[Immutability: ](http://blog.mgechev.com/2015/03/02/immutability-in-angularjs-immutablejs/)[Repo](https://github.com/mgechev/angular-immutable) [Details](http://victorsavkin.com/post/110170125256/change-detection-in-angular-2)</sub><br>
<sub>[JS Inheritance In Angular](http://blog.mgechev.com/2013/12/18/inheritance-services-controllers-in-angularjs/)</sub><br>
<sub>[Prototypes as Behaviors in Polymer](https://www.polymer-project.org/1.0/docs/devguide/behaviors)</sub><br>
<sub>[Prototypes as Custom Elements](https://www.polymer-project.org/1.0/docs/devguide/registering-elements)</sub>

Database - Provides both KV+SQL layers via browser & node 
<sub>[PouchDB](https://github.com/pouchdb/pouchdb)</sub><br>
<sub>[Lovefield](https://github.com/google/lovefield)</sub><br>

Clusters<br>
<sub>[PM2](https://github.com/Unitech/pm2) ([vs Node's cluster module](https://keymetrics.io/2015/03/26/pm2-clustering-made-easy/))</sub><br>
<sub>[Node Profiling](https://github.com/thlorenz/v8-perf/issues/4)</sub><br>
##### [<span class="octicon octicon-link"></span>](#credits)Credits<br>
<sub>Eric Bidelman's [Angular Using Polymer Elements](https://www.youtube.com/watch?v=p1NpZ-0Op0w)</sub><br>
<sub>Web Components [Angular-Polymer Interop](https://github.com/webcomponents/angular-interop)</sub><br>
<sub>[NG-Polymer-Elements](http://ngmodules.org/modules/ng-polymer-elements)</sub>

</article>


 <pre>
         DIAMONDS    

   CMD: [ d.js   ]  <-  crud runner
   VIEW: CR results, editor, or perf

      ON / OFF switch 
</pre>

