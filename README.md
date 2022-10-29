# JaVa_CoRe

## Numeric primitive casting
```
//Implicit casting
byte byteVar = 42;
short shortVar = byteVar;
int intVar = shortVar;
long longVar = intvar;
float floatVar = longVar;
double doubleVar = floatVar;
```

```
//Explicit casting
double doubleVar = 42.0d;
float floatVar = (float) doubleVar;
long longVar = (long) floatVar;
int intVar = (int) longVar;
short shortVar = (short) intVar;
byte byteVar = (byte) shortVar;
```

## Object casting
```
Float floatVar = new Float(42.0f);
Number n = floatVar; //Implicit (Float implements Number)
Float floatVar2 = (Float) n; //Explicit
Double doubleVar = (Double) n; //Throws exception (the object is not Double)
```

