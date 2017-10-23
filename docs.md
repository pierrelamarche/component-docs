1. [Class Selector](#class-selector)
2. [Bracket Input](#bracket-input)
3. [Secrets Radio Buttons](#secrets-radio-buttons)
4. [Quest Toggle](#quest-toggle)

### Class Selector
---
**Type:_** Dashboard Element

**_Description:_** 	A label, dropdown, and optional checkbox for all 9 Hearthstone classes (Druid, Hunter, Mage, 		Paladin, Priest, Rogue, Shaman, Warlock, Warrior)

**_Properties:_** 
* _Name_ (string) : used as the element Id
* _Toggle_ (boolean) : adds a checkbox toggle
* _Ban_ (boolean) : render ban version of dropdown

**_Example Use [Pug]:_** 
```
class-selector(name="3", toggle)
class-selector(name="4", ban)
```
**_Rendered View(s):_** 

![view](https://i.imgur.com/QsKKI1G.png)
![view](https://i.imgur.com/sTtvKYx.png)
![view](https://i.imgur.com/CHu7ugC.png)

### Bracket Input
---
**Type:_** Dashboard Element

**_Description:_** 	Creates n pairs of inputs for matches

**_Properties:_** 
* _Matches_ (int) : the total number of matches to render

**_Example Use [Pug]:_** 
```
bracket-inputs(matches="2")
```
**_Rendered View(s):_** 

![view](https://i.imgur.com/jHD9nsb.png)

### Secrets Radio Buttons
---
**Type:_** Dashboard Element

**_Description:_** 	A radio button set for the three secret types (mage, paladin, hunter)

**_Example Use [Pug]:_** 
```
secrets-radio
```
**_Rendered View(s):_** 

![view](https://i.imgur.com/J4ClXze.png)

### Quest Toggle
---
**Type:_** Dashboard Element

**_Description:_** 	A text input and show/hide buttons for a Quest label (i.e 2/7 progress)

**_Example Use [Pug]:_** 
```
quest-toggle
```
**_Rendered View(s):_** 

![view](https://i.imgur.com/FJciQ8U.png)
