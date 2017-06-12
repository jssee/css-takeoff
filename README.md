<h2 align="center">🛩️ CSS TAKEOFF 🛩️</h2>
<h5 align="center">Basic directory structure and base files to get a project started. Based on my needs, made up of some best practices and neat tricks picked up along the way.</h5>	

#### Methodology?
Sure. I try to loosely enforce the [GPS methodology](https://github.com/jescalan/gps) since it is lightweight and can easily be extended to the other more well known structure and file naming methodologies if the project calls for it. Its by no mean strict: *do what you want.*

#### Structure
```
css-takeoff/
|
|-- css/      # CSS pure structure, requires postcss-cssnext plugin to use custom media in settings.
|   |-- global/
|		|      |
|		|      |--_reset.css
|		|      |--_settings.css
|   |      `--_typography.css
|   |
|   |-- page/
|   |-- components/
|   `-- index.css
|
|
`-- stylus      # stylus structure
    |-- global/
    |				 |
    |				 |--_reset.styl       
    |				 |--_base.styl        
    |				 |--_mixins.styl      
    |				 |--_variables.styl   
    |				 `--_typography.styl 
    |
    |-- page/
    |-- components/
    `-- _master.styl         
```
