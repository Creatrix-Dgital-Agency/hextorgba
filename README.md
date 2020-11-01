# hextorgba
convert hex color to RGBA

#installation
yarn add @creatrix/hextorgba

or

npm i @creatrix/hextorgba

#example

import {convertHexToRGBA} from @creatrix/hextorgba;

const hexcolor='#FFF';

const converttorgba=convertHexToRGBA(hexcolor,'0.5') // rgba(255,255,255,0.5)
