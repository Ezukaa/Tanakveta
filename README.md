# Tanakveta
func Tanakveta(_ array1:[Int], array2:[Int])->[Int]{
    var array3 = [Int]()
    
    
    
    for item1 in array1{
    for item2 in array2{
        if item1==item2{
            array3.append(item1)
        }
    }
}
    return array3
}

 let array:[Int] = [100,200,177,140,4,1]
 let arrayy:[Int] = [100,200,150,4,1,3,9,10]

print(Tanakveta(array, array2:arrayy))
