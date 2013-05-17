Photoshop Effects Values
========================

## dropShadow

### Values

sepalater: '&'

1. enabled / desabled(boolean): 1 / 0
1. Opacity(%): 0.000000 - 100.000000
1. Lighting?(Fw is't using): 0
1. Angle(deg): 0.000000 - 359.999999
1. Noise(%): 0.000000 - 100.000000
1. Distance(px): 0.000000 - 30000.000000
1. Size(px): 0.000000 - 250.000000
1. Spread(%): 0.000000 - 100.000000
1. Shape AntiAlias(boolean): 0
1. Knock Out(boolean): 1
1. Brend Mode(string): multiply
1. Color(multiple, sepalater: ';'):
    * Color Mode(const): RGBColor
    * R channel: 0.000000 - 255.000000
    * G channel: 0.000000 - 255.000000
    * B channel: 0.000000 - 255.000000
1. Shape(multiple, sepalater: '$'):
    * Point Quantity(int): [2 - ?]$
    * Coordinate(multiple, sepalater: ';'): 
        * Coordinate X(number): 0.000000 - 255.000000
        * Coordinate Y(number): 0.000000 - 255.000000
        * Edge(boolean): 1 / 0

### Sample

1&75.000000&0&120.000000&0.000000&10.000000&3.000000&5.000000&1&1&multiply&RGBColor;0.000000;0.000000;0.000000&5$$0.000000;0.000000;1$66.000000;128.000000;0$127.000000;0.000000;0$191.000000;126.000000;0$255.000000;0.000000;1

### in Fireworks

* name: 'Drop Shadow'
* EffectIsVisibule: enabled
* category: 'Shadow and Glow'
* ShadowColor: Color RGB -> #rrggbbaa
* ShadowDistance: Distance
* ShadowType: Knock Out
* ShadowBlur: Size
* ShadowAngle: Angle
* EffectMoaID: '{a7944db8-6ce2-11d1-8c76000502701850}'
