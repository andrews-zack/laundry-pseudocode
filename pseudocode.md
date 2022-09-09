## PSEUDOCODE PROJECT
<br>

### How to do laundry
<br>

#### **About**
* The modern task of laundry revolves around the use of a washing machine and a dryer.
* The washing machine requires water, detergent, and clothes to work as intended.
* After completion of the washing cycle, the clothes are then transferred to the dryer.
* Once the dryer finishes, the user must hang up the shirts, fold pants/shorts, and bundle socks.
<br>

#### **INIT**
<br>

##### Declaring variables for the process
<br>

**Clothes**
* The object that we are washing.
* Can be shirts, pants/shorts, or socks.
*Properties*
`clothesDryness`
`clothesColor`
`clothesType`
<br>

**Washing Machine**
* Tool used to clean the clothes
* Requires some user input
* Water used determined by cycle size

*Properties*
`cycleSize`
<br>

**Water**
* Used during the washing cycle
* Added by the washing maching
* Is a different temperature depending on the color of the clothes being washed

*Properties*
`waterAmount`
`waterTemperature`
<br>

**Detergent**
* The soap used by the washer to clean the clothes
* Put in before the wash cycle with the clothes

*Properties*
    `detergentAmount`
<br>

**Dryer**
* Tool used to dry the clean clothes
* Requires some user input

*Properties*
    `dryerTemp`

**Hangers**
* Used to hang up shirts after they are dry

*Properties*
    `hangerAmount`
<br>

#### **FUNCTIONALITY**

```
function sortClothes() {
    let clothing = [shirts, pants, socks]
    let washingMachine = []
    for (clothes of clothing)
    if clothes.clothesColor !== white {
        washingMachine.push(clothes)
        else {
            put back in hamper
        }
    }
}



```
