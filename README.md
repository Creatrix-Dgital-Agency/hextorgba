# hextorgba
convert hex color to RGBA

yarn add @creatrix/hextorgba

OR

npm i @creatrix/hextorgba


import {convertHexToRGBA} from @creatrix/hextorgba;

const hexcolor='#FFF';

const converttorgba=convertHexToRGBA(hexcolor,'0.5') // rgba(255,255,255,0.5)
