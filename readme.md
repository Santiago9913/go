# Datos Primitivos

## Numeros enteros

- int = Depende del OS (32 o 64 bits)
- int8 = 8 bits = -128 a 127
- int16 = 16 bits = 2<sup>-15</sup> a 2<sup>15</sup> - 1
- int32 = 32 bits = 2<sup>-31</sup> a 2<sup>31</sup> - 1
- int64 = 64 bits = 2<sup>-63</sup> a 2<sup>63</sup> - 1

## Numero enteros positivos

- uint = Depende del OS (32 o 64 bits)
- uint8 = 8 bits = 0 a 128
- uint16 = 16 bits = 0 a 2<sup>16</sup> - 1
- uint32 = 32 bits = 0 a 2<sup>32</sup> - 1
- uint64 = 64 bits = 0 a 2<sup>64</sup> - 1

## Numeros decimales

- float32 = 32 bits = +/- 1.18e<sup>-38</sup> a +/- 3.4e<sup>38</sup>
- float64 = 64 bits = +/- 2.23e<sup>-308</sup> a +/- 1.8e<sup>308</sup>

## Texto y boleanos

- string = ""
- bool = true o false

## Numeros complejos

- Complex64 = Real e imaginario float32
- Complex128 = Real e imaginario float64
- Ejemplo
  ```go
  c:= 10 + 8i
  ```
