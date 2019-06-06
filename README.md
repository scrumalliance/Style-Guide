# :art: Style Guide
[Scrum Alliance Style & Components](https://projects.invisionapp.com/share/QMJGWVZU69R#/screens/303774429)
[Wireframes & Mockups] (https://projects.invisionapp.com/share/QMJGWVZU69R#/screens/298438531)

## Typography 

### Typeface
- Clear Sans Regular
- Clear Sans Thin
- Clear Sans Medium 
- Clear Sans Bold

### Titles
- Title Display (H1)  | `font-size: 60px; letter-spacing: -1.0px;`
- Title Page (H2)     | `font-size: 36px;`
- Title Large (H3)    | `font-size: 28px;`
- Title Medium (H4)   | `font-size: 22px; letter-spacing: -0.2px;`
- Title Small (H5)    | `font-size: 18px; letter-spacing: -0.2px;`
- All Caps Large (H6) | `font-size: 18px; letter-spacing: 1.6px; text-transform: uppercase;`
- All Caps Small (H7) | `font-size: 15px; letter-spacing: 2.0px; text-transform: uppercase;` 

### Body
- Body Large    | `font-size: 20px; letter-spacing: -0.2px;`
- Body Medium   | `font-size: 17px;`
- Body Small    | `font-size: 15px; letter-spacing: 0.2px;`
- Body XSmall   | `font-size: 13px;`


## Colors
- ![#009FDA](https://placehold.it/15/009FDA/000000?text=+) `#009FDA` | PRO CYAN *links & primary button rest* 
- ![#45BBE6](https://placehold.it/15/45BBE6/000000?text=+) `#45BBE6` | LIGHT PRO CYAN *primary button hover*
- ![#25495C](https://placehold.it/15/25495C/000000?text=+) `#25495C` | BLUE GREY *secondary button*
- ![#1C638A](https://placehold.it/15/1C638A/000000?text=+) `#1C638A` | NAVY *link hover and active*
- ![#00998F](https://placehold.it/15/00998F/000000?text=+) `#00998F` | TEAL
- ![#41A341](https://placehold.it/15/41A341/000000?text=+) `#41A341` | DARK GREEN
- ![#4BBD4B](https://placehold.it/15/4BBD4B/000000?text=+) `#4BBD4B` | GREEN
- ![#EBB400](https://placehold.it/15/EBB400/000000?text=+) `#EBB400` | YELLOW
- ![#21343D](https://placehold.it/15/21343D/000000?text=+) `#21343D` | DARK GREY *headers*
- ![#374C57](https://placehold.it/15/374C57/000000?text=+) `#374C57` | GREY *body*
- ![#5B7380](https://placehold.it/15/5B7380/000000?text=+) `#5B7380` | LIGHT GREY *supplemental text*
- ![#94A7B0](https://placehold.it/15/94A7B0/000000?text=+) `#94A7B0` | SLATE *hint text*
- ![#C3D0D6](https://placehold.it/15/C3D0D6/000000?text=+) `#C3D0D6` | SILVER *borders*
- ![#F5F8FA](https://placehold.it/15/F5F8FA/000000?text=+) `#F5F8FA` | OFF-WHITE *background*
- ![#FFFFFF](https://placehold.it/15/FFFFFF/000000?text=+) `#FFFFFF` | WHITE


## Spacing
- `6px;`
- `8px;`
- `16px;`
- `24px;`
- `36px;`
- `60px;`
- `80px;`


## Buttons 
- Base Button: `display: inline-block; font-weight: 400; text-align: center; white-space: nowrap; vertical-align: middle; -webkit-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none; border: 1px solid transparent; padding: .375rem .75rem; font-size: 1rem; line-height: 1.5; border-radius: .25rem; transition: color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out,box-shadow .15s ease-in-out;`

- Primary: `background-color: #009FDA; color: #FFFFFF; border-color: #009FDA;`

- Primary:hover, :active, :visited: `background-color: #45BBE6; border-color: #45BBE6;`

- Primary on Dark: `border-color: #FFFFFF; background-color: transparent; color: #FFFFFF;`

- Primary on Dark:hover, :active, :visited: `border-color: #009FDA; background-color: #009FDA; color: #FFFFFF;`

- Secondary: `border-color: #25495C; color: #2495C; background-color: #FFFFFF;`

- Secondary:hover, :active, :visited: `border-color:#25495C; color: #FFFFFF; background-color: #25495C;`

- Secondary on Dark: `border-color: #FFFFFF; background-color: #25495C color: #FFFFFF;`

- Secondary on Dark:hover, :active, :visited: `border-color: #FFFFFF; background-color: #FFFFFF; color: #25495C;`

## Links 
- Primary Link: `.SAPrimaryLink:link { color: #009FDA; text-decoration: none; font-weight: bold; }`
`.SAPrimaryLink:hover, .SAPrimaryLink:active, .SAPrimaryLink:visited { color: #25495C; text-decoration: none; font-weight: bold; }`
    
- Secondary Link: `.SASecondaryLink:link { color: #25495C; text-decoration: none; font-weight: bold; }`
`.SASecondaryLink:hover, .SASecondaryLink:active, .SASecondaryLink:visited { color: #009FDA; text-decoration: none; font-weight: bold; }`

## Switches
```
<label class="switch">
  <input type="checkbox">
  <span class="slider"></span>
</label>

<label class="switch">
  <input type="checkbox" checked>
  <span class="slider"></span>
</label>
```

`.switch { position: relative; display: inline-block; width: 60px; height: 34px; }`

`.switch input { opacity: 0; width: 0; height: 0; }`

`.slider { position: absolute; cursor: pointer; top: 0; left: 0; right: 0; bottom: 0; background-color: #94A7B0; /* Alternative: background-color: #5B7380; */ -webkit-transition: .4s; transition: .4s; border-radius: 34px; }`

`.slider:before { position: absolute; content: ""; height: 26px; width: 26px; left: 4px; bottom: 4px; background-color: white; -webkit-transition: .4s; transition: .4s; border-radius: 50%; }`

`input:checked + .slider { background-color: #4BBD4B; /* Alternative: background-color: #41a341; */ }`

`input:focus + .slider { box-shadow: 0 0 1px #4BBD4B; /* Alternative:  box-shadow: 0 0 1px #41a341; */ }`

`input:checked + .slider:before { -webkit-transform: translateX(26px); -ms-transform: translateX(26px); transform: translateX(26px); } `

## Checkboxes
```
<label class="container">Checkbox Unselected
  <input type="checkbox">
  <span class="checkbox"></span>
</label>
<label class="container">Checkbox Selected
  <input type="checkbox" checked>
  <span class="checkbox"></span>
</label>
```

`/* The container */`
`.container { display: block; position: relative; padding-left: 36px; margin-bottom: 16px; cursor: pointer; font-size: 20px; -webkit-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none; }`

`/* Hide the browser's default checkbox */`
`.container input { position: absolute; opacity: 0; cursor: pointer; height: 0; width: 0; }`

`/* Create a custom checkbox */`
`.checkbox { position: absolute; top: 0; left: 0; height: 20px; width: 20px; background-color: #fff; border: 1px solid #374c57; border-radius: 4px; }`

`/* On mouse-over, the border darkens */`
`.container:hover input ~ .checkbox { border: 1px solid #21343D; }`

`/* When the checkbox is checked, add a dark grey background */`
`.container input:checked ~ .checkbox { background-color: #374c57; }`
`.container input:checked:hover ~ .checkbox { background-color: #21343d; }`

`/* Create the checkmark/indicator (hidden when not checked) */`
`.checkbox:after { content: ""; position: absolute; display: none; }`

`/* Show the checkmark when checked */`
`.container input:checked ~ .checkbox:after { display: block; }`

`/* Style the checkmark/indicator */`
`.container .checkbox:after { left: 6px; top: 2px; width: 5px; height: 10px; border: solid white; border-width: 0 3px 3px 0; -webkit-transform: rotate(45deg); -ms-transform: rotate(45deg); transform: rotate(45deg); }`
