Add your answers to the Algorithms exercises here.

Exercise I:

a) O(n) 
b) O(log n) 
c) O(n^2) 
d) O(n^2) 
e) O(n^3) 
f) O(n) 
g) O(n)

Exercise II:

a) 

const max =  diff(arr) { 
    let min = arr[0] 
    let difference = 0;

    for (let i = 0; i < arr.length; i++) { 
        min = Math.min(min, arr[i]); 
        difference = Math.max(difference, arr[i] - min) 
        } 
        
    return difference 
}

b)

We can use binary thinking. Start at f' = n/2. If egg breaks, set f' = f'/2. If egg does not break, set f' = 3f'/2

Exercise III:


a) 0(n^2) because we would be checking each item recursively.

b)Each recursive call will divide the array in half so 0(log(n))