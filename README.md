<article class="markdown-body entry-content" itemprop="mainContentOfPage">

![Diamonds Logo](https://i.ibb.co/p3LtTMW/687474703a2f2f63696e656d61636c6f75642e636f2f6469616d6f6e64737461636b2e706e673f3538.png?3)

**Diamonds** are isomorphic seeds & generators for Angular/Polymer ⇄ Express **distributed microservice** web & native apps.<br>
Diamond units provide clustering for unified custom facets as edge pages aka 'apps' and web components.<br>


##### **Generators**
![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `$> ./d.js (c|r|u|d) [type] Element_Name(+pattern)`<br><br>
[![](https://i.ibb.co/ch0gxQh/687474703a2f2f63636c642e74762f636c6f75645f6661636574732e706e673f2e3531.png?.52)](#)

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

| <img src=https://i.ibb.co/3NVrFS0/stamp.png width=128 height=128> | <img src=https://i.ibb.co/8sgC1rL/closure.png width=128 height=128> | <img src=https://i.ibb.co/fXBs3Qh/deploy.png width=128 height=128> |
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
typeorm<br>
bluebird<br>
grunt-ts<br>
yarn<br>
pm2<br>
web-component-tester.</sup>

##### [<span class="octicon octicon-link"></span>](#source-projects)Source Projects
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

Database (ORM)<br>
<sub>[TypeORM](https://github.com/typeorm/typeorm)</sub><br>

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

