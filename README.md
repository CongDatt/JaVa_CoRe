# JaVa_CoRe

## Primitive Data Types
- 8 primitive data types:
    1. byte: 
    2. short: 
    3. int: 
    4. long:
    5. char:
        - Có thể lưu 16-bit
        - ``` char myChar = u ```
    6. boolean: 
    7. float:
    8. double:

## Coverting Primitives
- Có 2 kiểu chuyển đổi kiểu dữ liệu
    1. widening conversion
        - ``` int a = 1; 
            double d = a; // valid conversion to double, no (widening
            ```
    2. narrowing conversion.
        - ```         double b = 18.94;
            int c = (int) b;  ```


## Memory consumption of primitives vs. boxed primitives
boolean / Boolean => 1 byte / 16 bytes
byte / Byte => 1 byte / 16 bytes
short / Short => 2 bytes / 16 bytes
char / Char => 2 bytes / 16 bytes
int / Integer => 4 bytes / 16 bytes
long / Long => 8 bytes / 16 bytes
float / Float => 4 bytes / 16 bytes
double / Double => 8 bytes / 16 bytes
 
