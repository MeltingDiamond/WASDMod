# WASD mod for The Bibites
This mod lets you control the bibites with the keyboard or the mouse

## Install instructions:
Read all the instructions before you follow them.

To install, download The Bibites version 0.5.1 and replace "The Bibites_data/Managed/BibitesAssembly.dll" with the corresponding dll found here.
Then you can start The Bibites as usual.

If you want to use a premade bibite open the bibites folder and download the bibite you want to use. Then open C:\Users\user\AppData\LocalLow\The Bibites\The Bibites\Bibites\Templates and paste the bibites there.
After doing that you can spawn them as usual.

## How to make a bibite compatible with the WASD mod
Open the bibite in a text editor, then replace the Nodes with:
```
  "nodes": [
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 0,
      "Inov": 0,
      "Desc": "Constant",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 1,
      "Inov": 0,
      "Desc": "EnergyRatio",
      "Value": 0.9471614,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 2,
      "Inov": 0,
      "Desc": "Maturity",
      "Value": 0.251997471,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 3,
      "Inov": 0,
      "Desc": "LifeRatio",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 4,
      "Inov": 0,
      "Desc": "Fullness",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 5,
      "Inov": 0,
      "Desc": "Speed",
      "Value": 1.27547908,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 6,
      "Inov": 0,
      "Desc": "IsGrabbing",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 7,
      "Inov": 0,
      "Desc": "AttackedDamage",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 8,
      "Inov": 0,
      "Desc": "BibiteCloseness",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 9,
      "Inov": 0,
      "Desc": "BibiteAngle",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 10,
      "Inov": 0,
      "Desc": "NBibites",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 11,
      "Inov": 0,
      "Desc": "PlantCloseness",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 12,
      "Inov": 0,
      "Desc": "PlantAngle",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 13,
      "Inov": 0,
      "Desc": "NPlants",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 14,
      "Inov": 0,
      "Desc": "MeatCloseness",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 15,
      "Inov": 0,
      "Desc": "MeatAngle",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 16,
      "Inov": 0,
      "Desc": "NMeats",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 17,
      "Inov": 0,
      "Desc": "RedBibite",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 18,
      "Inov": 0,
      "Desc": "GreenBibite",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 19,
      "Inov": 0,
      "Desc": "BlueBibite",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 20,
      "Inov": 0,
      "Desc": "Tic",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 21,
      "Inov": 0,
      "Desc": "Minute",
      "Value": 0.200311586,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 22,
      "Inov": 0,
      "Desc": "TimeAlive",
      "Value": 0.200311586,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 23,
      "Inov": 0,
      "Desc": "PheroSense1",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 24,
      "Inov": 0,
      "Desc": "PheroSense2",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 25,
      "Inov": 0,
      "Desc": "PheroSense3",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 26,
      "Inov": 0,
      "Desc": "Phero1Angle",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 27,
      "Inov": 0,
      "Desc": "Phero2Angle",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 28,
      "Inov": 0,
      "Desc": "Phero3Angle",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 29,
      "Inov": 0,
      "Desc": "Phero1Heading",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 30,
      "Inov": 0,
      "Desc": "Phero2Heading",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 31,
      "Inov": 0,
      "Desc": "Phero3Heading",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 32,
      "Inov": 0,
      "Desc": "InfectionRate",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 33,
      "Inov": 0,
      "Desc": "Up/Down",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 34,
      "Inov": 0,
      "Desc": "Left/Right",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 35,
      "Inov": 0,
      "Desc": "MouseCloseness",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 36,
      "Inov": 0,
      "Desc": "MouseAngle",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 37,
      "Inov": 0,
      "Desc": "remappable1",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 38,
      "Inov": 0,
      "Desc": "remappable2",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 39,
      "Inov": 0,
      "Desc": "remappable3",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 40,
      "Inov": 0,
      "Desc": "remappable4",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 41,
      "Inov": 0,
      "Desc": "remappable5",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 0,
      "TypeName": "Input",
      "Index": 42,
      "Inov": 0,
      "Desc": "remappable6",
      "Value": 1.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 3,
      "TypeName": "TanH",
      "Index": 43,
      "Inov": 0,
      "Desc": "Accelerate",
      "Value": 0.6929418,
      "LastInput": 0.8535929,
      "LastOutput": 0.6929418
    },
    {
      "Type": 3,
      "TypeName": "TanH",
      "Index": 44,
      "Inov": 0,
      "Desc": "Rotate",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 3,
      "TypeName": "TanH",
      "Index": 45,
      "Inov": 0,
      "Desc": "Herding",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 1,
      "TypeName": "Sigmoid",
      "Index": 46,
      "Inov": 0,
      "Desc": "Want2Lay",
      "Value": 0.5,
      "LastInput": 0.0,
      "LastOutput": 0.5
    },
    {
      "Type": 1,
      "TypeName": "Sigmoid",
      "Index": 47,
      "Inov": 0,
      "Desc": "Want2Eat",
      "Value": 0.5,
      "LastInput": 0.0,
      "LastOutput": 0.5
    },
    {
      "Type": 1,
      "TypeName": "Sigmoid",
      "Index": 48,
      "Inov": 0,
      "Desc": "Digestion",
      "Value": 0.11235629,
      "LastInput": -2.06689548,
      "LastOutput": 0.11235629
    },
    {
      "Type": 3,
      "TypeName": "TanH",
      "Index": 49,
      "Inov": 0,
      "Desc": "Grab",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 1,
      "TypeName": "Sigmoid",
      "Index": 50,
      "Inov": 0,
      "Desc": "ClkReset",
      "Value": 0.5,
      "LastInput": 0.0,
      "LastOutput": 0.5
    },
    {
      "Type": 5,
      "TypeName": "ReLu",
      "Index": 51,
      "Inov": 0,
      "Desc": "PhereOut1",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 5,
      "TypeName": "ReLu",
      "Index": 52,
      "Inov": 0,
      "Desc": "PhereOut2",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 5,
      "TypeName": "ReLu",
      "Index": 53,
      "Inov": 0,
      "Desc": "PhereOut3",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    },
    {
      "Type": 1,
      "TypeName": "Sigmoid",
      "Index": 54,
      "Inov": 0,
      "Desc": "Want2Grow",
      "Value": 0.5,
      "LastInput": 0.0,
      "LastOutput": 0.5
    },
    {
      "Type": 1,
      "TypeName": "Sigmoid",
      "Index": 55,
      "Inov": 0,
      "Desc": "Want2Heal",
      "Value": 0.5,
      "LastInput": 0.0,
      "LastOutput": 0.5
    },
    {
      "Type": 1,
      "TypeName": "Sigmoid",
      "Index": 56,
      "Inov": 0,
      "Desc": "Want2Attack",
      "Value": 0.5,
      "LastInput": 0.0,
      "LastOutput": 0.5
    },
    {
      "Type": 3,
      "TypeName": "TanH",
      "Index": 57,
      "Inov": 0,
      "Desc": "ImmuneSystem",
      "Value": 0.0,
      "LastInput": 0.0,
      "LastOutput": 0.0
    }
  ],
```
Then add 10 to the synapse NodeOut on all the synapses so they correspond to the correct output neuron.
So if this is the synapes:
```    {
      "Inov": 0,
      "NodeIn": 0,
      "NodeOut": 33,
      "Weight": 0.4535929,
      "En": true
    },
```
You change it to:
```    {
      "Inov": 0,
      "NodeIn": 0,
      "NodeOut": 43,
      "Weight": 0.4535929,
      "En": true
    },
```
Then save and test it in in a WASD mod sim. 

### Problems you might encounter
Head over to [the unofficial bibites discord server](https://discord.gg/rNDMdNjQ2R) and ask in [modding-chat](https://discord.com/channels/1059654549650034748/1203723252350844988) for help installing.
If you got questions spesifically to this mod go to [WASD mod](https://discord.com/channels/1059654549650034748/1209160253183361064).
If no one answers you feel free to ping @melting_diamond which is the creator of this mod.
