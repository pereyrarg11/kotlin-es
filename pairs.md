# Pares

Permiten almacenar asociaciones de datos en una estructura de clave-valor.
Es posible que el par contenga claves y valores de distinto tipo.

~~~
val coordinates : Pair<Int, Int> = Pair(25, 16)
val month = 1 to "Enero"

println("coordinates $coordinates")
println("month $month")

/*
* output:
* coordinates (25, 16)
* month (1, Enero)
* */
~~~

