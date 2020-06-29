# What-I-Learn-Week-6

## Hip-Hip Array
* _.repeat()_ - can repeat item from an array without a loop
* _.push()_ / _.shift()_ - for removing first and last items from an array
* _.unshift()_ - append to the beginning of an array an item.
* _.splice(start, countOfItemsToRemoveFromStart, itemToAdd1, itemToAdd2...)_ - using splice we can remove items from start of index, count of items to remove and then also add items at the beginning of that start index after the count removed.
* _.slice(start, end)_ - based on zero start index if start is specified removes that item all the way up to end index ei. .slice(1,3) removes from index 1, 2, 3. Returns new array with extracted items.
* _.concat()_ - concatonates two or more arrays together and returns new array with all items from both or more array together.
* _.join('CharacterToJoinWith')_ - using this method we can join items together into one string. Basically we are making a string out of items from an array and if passing a string inside paranthesis we can join items with any character or string between items of an array.

## Cat's Cradle - A String Looping Exercise

* While loops.
* String indices.
function vowelsOnly(string){
let i = 0
const vowels = 'aeiou'
    while(i < string.length){
        if (vowels.includes[string[i]] && count < 5){
            console.log(string[i])
        }
        i = i + 1
    }
}

# Whiling Away

let num =1 ;
while (num <= 5) {
    console.log(num);
    num =num +1 ;
} 

num = 1
function countHello(){
while (num <= 7){
    console.log(num + '. '+'Hello!')
    num = num + 1
}
}
countHello()
