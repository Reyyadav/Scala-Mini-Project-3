# Scala-Mini-Project-3 

# Functions + Class

## - We are writing a program for basic Operations.
## - Write a Class Number that will store a value in it.
## - Write a Function in the class Number that will take class Number as the parameter and Return the sum of the teo classes value.
## - Write a Function in the class Number that will take Class Number as the parameter and Return true if , parameter, Number class, value is greater than the calling class value else return false.




## Code solution :

                                              
                                               
                                               object main{
                      
                          class Number(var value:Int){
                      
                            def print_value():Unit={
                              println(value)
                              
                            }
                            def sum(n:Number):Unit={
                              println(value+n.value)
                            }
                      
                            def isGreater(n:Number):Boolean={
                              if(n.value<value){
                                return true
                              }
                              else{
                                return false
                              }
                            }
                          }
                          def main(args: Array[String]): Unit ={
                            var n1 = new Number(10)
                            var n2 = new Number(20)
                            var n3 = new Number(30)
                      
                            n1.sum(n3)
                            println(n1.isGreater(n2))
                            
                          }
                        }

                        

# function call


![Screenshot 2024-05-16 121237](https://github.com/Reyyadav/Scala-Mini-Project-3/assets/153619494/e5f5507e-9b27-4283-9a49-0d2a98614bc0)


# Output


![Screenshot 2024-05-16 121245](https://github.com/Reyyadav/Scala-Mini-Project-3/assets/153619494/6076ca99-1f20-4f0e-9a31-adf11fd52627)
