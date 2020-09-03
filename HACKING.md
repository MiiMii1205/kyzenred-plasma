# Kyzenred Hacking

So you want to extend the theme, yes? First up, let's talk about what you'll need!

first, you need to know that Kvantum is a pure SVG engine. This means that if you want to change things you'll need to know how SVGs works, along with good HTML and CSS knowledge. 

Thankfully, there's [w3school](https://www.w3schools.com/graphics/svg_intro.asp). With their little SVG reference you'll be ready in no time to edit the theme!

Also, to render properly, Kyzenred uses the included plasma theme renderer. There's a nice [KDE's plasma theming guide](https://techbase.kde.org/Development/Tutorials/Plasma5/ThemeDetails) for those who are interested.

## Recoloring
Kyzenred is dynamically colored theme. This means that its components are dynamically recolored based on the current color scheme.

Because KDE's plasma theming engine natively support recoloring, there's no real need for additional scripts. 

In essence, a special CSS stylesheet is applied when Plasma renders an SVG.

This stylesheet contains special CSS classes with color scheme specific colors. 

Each of these classes can be used on an SVG element to give them unique colors.

If you want to know more about it, I suggest you take a look at [KDE's plasma theming guide](https://techbase.kde.org/Development/Tutorials/Plasma5/ThemeDetails). 