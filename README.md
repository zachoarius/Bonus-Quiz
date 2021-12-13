// # Bonus-Quiz
// This is an extra credit assignment.
import io.StdIn._
println(“This program will calculate the distance between (x1, y1) and (x2, y2)”)
println(“x1”)
val v = readInt()
println(“x2”)
val w = readInt()
println(“y1”)
val x = readInt()
println(“y2”)
val y = readInt()
val z = math.sqrt(math.pow((w-v),2)+math.pow((y-x),2))
var str1 = “The distance between (“ + v + “, ” + w + “) and (“ + x + “, ” + y “) is “ + z
print(str1) //
