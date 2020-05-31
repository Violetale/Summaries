## DATA STRUCTURES 

### STUCK

This data structure is based on a principle *LIFO (Last In - First Out). *
* Stack has methods:  *
-push: add new element
-pop: delete and return last element
-pick: return last element
-length: return size of stuck

``` 
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
            return this.count;
        }
    }
```

### Queue

A queue resembles a stack. The difference is that the queue follows the rule *FIFO (First In-First Out). *
* Stack has methods: *
-enqueue: add element at the end of the queue
-dequeue: delete and return first element 
-front : return first element
-isEmpty : check if queue is empty
-size: return a count of elements in queue

``` 
class Queue{
    constructor(){
        this.collection =[]
    }
    print(){
        console.log(collection);
    }
    enquene(element){
        collection.push(element);
    }
    front(){
        return collection[0];
    }
    isEmpty(){
        return collection.length ===0;
    }
    size(){
        return collection.length;
    }
}
```

###