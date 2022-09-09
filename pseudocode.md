## PSEUDOCODE PROJECT
<br>

## How to do laundry
<br>

### **About**
* The modern task of laundry revolves around the use of a washing machine and a dryer.
* The washing machine requires water, detergent, and clothes to work as intended.
* After completion of the washing cycle, the clothes are then transferred to the dryer.
* Once the dryer finishes, the user must hang up the shirts, fold pants/shorts, and bundle socks.
<br>

### **INIT**
<br>

#### Declaring variables for the process
<br>

#### **Clothes**
* The object that we are washing.
* Can be shirts, pants/shorts, or socks.

    *Properties*
    * `clothesDryness`
    * `clothesColor`
    * `clothesType`
<br>

**Washing Machine**
* Tool used to clean the clothes
* Requires some user input
* Water used determined by cycle size

    *Properties*
    * `washCycleSelect`
<br>

**Water**
* Used during the washing cycle
* Added by the washing maching
* Is a different temperature depending on the color of the clothes being washed

    *Properties*
    * `waterAmount`
    * `waterTemperature`
<br>

**Detergent**
* The soap used by the washer to clean the clothes
* Put in before the wash cycle with the clothes

    *Properties*
    * `detergentAmount`
<br>

**Dryer**
* Tool used to dry the clean clothes
* Requires some user input

    *Properties*
    * `dryerCycleSelect`
    * `lintScreen`

**Hangers**
* Used to hang up shirts after they are dry

    *Properties*
    * `hangerAmount`
<br>

#### **FUNCTIONALITY**

```
function sortColors
    let clothing = [shirts, pants, socks]
    let washingMachine = []
    let clothesColor = color of the clothing
    FOR (clothes of clothing)
    IF clothesColor !== white 
        THEN washingMachine.push(clothes)
        ELSE
            put back in hamper

function addDetergent
    let detergentAmount = how much detergent is in the measuring cap
    IF (detergentAmount === max fill line)
        THEN pour into washingMachine

function washCycle
    let cycleSelect = preset options for different washes on the washing machine
    let waterTemperature = if the water that comes out of the washing machine is hot or cold
    IF (clothesColor !== white)
        let cycleSelect = colors
        let waterTemperature = cold
        ELSE
        let cycleSelect = whites
        let waterTemperature = warm

function transferClothes
    let waterAmount = how much water is in the washing machine
    IF (waterAmount === 0)
        THEN take clothes from washing machine and place them in the dryer

function dryCycle
    let dryerCycleSelect = preset options for different loads on the dryer
    let lintScreen = amount of lint on the catch screen in the dryer
    IF (lintScreen === clean)
        let dryerCycleSelect = normal dry
        ELSE
        Smokey the Bear says clean the lint screen

function dumpClothesOnBed
    let clothesDryness = how dry the clothes are
    if (clothesDryness === satisfactory)
        THEN take clothes from dryer and move them to the bed

function foldClothes
    let clothesType = whether it is a shirt, pants, or socks
    let hangerAmount = however many shirts were washed and dried
    FOR (clothesType of clothing)
    IF (clothesType = shirt)
        THEN hang up the shirt in the closet, (hangerAmount--)
        ELSEIF (clothesType = pants)
            THEN fold pants and put them in the dresser
            ELSE
                bundle similar socks together and put them away
```
<br>

### START

```
sortColors
addDetergent
washCycle
addEventListener('ding', transferClothes)
dryCycle
addEventListener('ding2', dumpClothesOnBed)
foldClothes
```

### END
