## Base dự án HTML/CSS ban đầu.

### Code reset.css mẫu:

#### Truy cập link sau: [Truy cập](http://meyerweb.com/eric/tools/css/reset/)

```css
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
   margin: 0;
   padding: 0;
   border: 0;
   font-size: 100%;
   font: inherit;
   vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
   display: block;
}
body {
   line-height: 1;
}
ol,
ul {
   list-style: none;
}
blockquote,
q {
   quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
   content: "";
   content: none;
}
table {
   border-collapse: collapse;
   border-spacing: 0;
}
```

### Code mẫu base dự án thực tế:

> [!NOTE]\
> *, :root, html

```css
* {
   box-sizing: inherit;
}

:root {
   --color-primary: #007bff;
   --color-secondary: #6c757d;
   --color-success: #28a745;
   --color-danger: #dc3545;
   --color-warning: #ffc107;
   --color-info: #17a2b8;
   --color-light: #f8f9fa;
   --color-dark: #343a40;
   --color-white: #fff;
   --color-black: #000;
}

html {
   font-size: 62.5%;
   box-sizing: border-box;
   font-family: "Courier New", Courier, monospace;
}
```
