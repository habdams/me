### imports
- Third party 
- Console components
- imports relative to current file
* Sections separated by new lines.

### classname
- className should look like this:
`className={c(className, 'module classes', 'global classes', classFromProp, { conditional: true })}`


I.e. className prop from outside > style.module.scss classes > global CSS classes > classes that are generated dynamically (e.g. size in ) and classes that you want to toggle based on a boolean.

### setting parameters for a component
Nitpick: (required parameters > optional parameters > required function parameters > optional function parameters)