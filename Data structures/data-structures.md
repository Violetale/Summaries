## DATA STRUCTURES 

### STUCK

This data structure is based on a principle *LIFO (Last In - First Out). *
*Stack has methods: *
-push: add new element
-pop: delete and return last element
-pick: return last element
-length: return size of stuck

    class Stuck{
        constructor(){
            this.count=0,
            this.storage=[]
        }
        push(elem){
            this.storage[this.count]=elem;
            this.count++
        }
        pop(){
            if(this.count===0){
                return undefined
            }
            let lastElem=this.storage[this.count];
            delete this.storage[this.count];
            returl lastElem;
        }
        pick(){
            return this.storage[this.count];
        }
        size(){
            return this.cpunt;
        }
    }

