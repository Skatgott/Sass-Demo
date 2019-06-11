# Exercise for Sass-Demo

In the html-folder is a html-file (table.html) of the final table of the Bundesliga 2018/19. This table appears without any styling settings.

Your task is to write a Sass-file that paint the rows of the table in different colors due to the achievements of the teams. This file must be named "style.scss" so the created CSS file gets the fitting name.

## Partials / Imports

At first, import the already existing _basicstyle.scss file for getting first font styles.

## Mixins

The table cells already got style classes like "td-champion-l". -l and -r should be set as left and right alignment.
Write a mixin so each td-... -rule only has to include the mixin.
- Use parameters for that.
- Use variables for the different colors.
- Add some additional padding rules to the mixin.

## Inheritance

The last task is to add the correct colors to the labels below the table.
With the styles
```
border-left: 1.2em solid;
padding-left: 0.5em;
```
you can make the boxes left of the texts visible.
Use the inheritance feature so that you only need to add the correct
```
border-left-color: ...
```

## Possible final results

You can find a possible solution of the Sass-file [here](https://github.com/Skatgott/Sass-Demo/tree/master/html). The created style.css file can be found in the same folder.
