# tooltip
simple js css tooltip

to install:
```
npm i @sohrabi2050/tooltip
```

how to import:
```
import { initTooltip } from "@sohrabi2050/tooltip";
```

how to use:

<table border="1">
    <tr><th>option</th><th>description</th></tr>
    <tr><tr><td>tooltip</td><td>Text to show as tooltip</td></tr>
    <tr>
        <td>positions</td>
        <td>Comma separated list of positions to change the positioning<br />
        default priority is as follow:
        <br />
        bottom, 
        top, 
        right, 
        left, 
        bottomleft, 
        bottomright, 
        topleft, 
        topright
        </td>
    </tr>
</table>

<hr/>


```
<span data-tooltip="test tooltip" data-positions="right,top">hover me to show tooltip</span>
```

```
initTooltip();
```
