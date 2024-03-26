### Data Types

#### Typescriptda 7 xil primative turdagi data typelar bor ular:

- string
- number
- bigInt
- boolean
- undefined
- null
- symbol

Typescriptda primative turga tegishli o'zgaruvchilar e'lon qilinganda type lari ham o'zgaruvchi yonidan yoziliwi kerak.

Masalan:

let str:string = "Boys' King"

### Union types

O'zgaruvchi bir yoki undan ko'proq (data type) qabul qilishi mumkin bo'lsa bu - UNION TYPE deb ataladi.

Masalan:

let age: nmuber| string
age = 26
age = "26"

### Literal type

LITERAL TYPE da biz o'zgaruvchi uchun aniq beligilangan (qiymat) larga murojaat qilishimiz mumkin.

Masalan:

let direction: "Up" | "Down"
direction = "Up

### Tuple

TUPLE - belgilangan o'lchamli arrayning maxsus turi && har bir indeksda ma'lum ma'lumotlar turlari bo'ladi. Ular oddiy arraylarga qaraganda qattiqroq.

Masalan:

let options:[string, number],
options = ["BK", 20]

### OBJECT

Typescriptda OBJECT e'lon qilayotganda biz object ichidagi har bir key qaysi turdagi (data type) ga mansubligini bildirishimiz lozim.

Masalan:

let person:{
name:string
isProgrammer:boolean
}

person = {
name:Abdulloh
isProgrammer: true
}

### ARRAY

Biz ARRAY ichida kelgan ma'lumotlarni bila olmasligimiz mumkin ammo ularning turlarini aniqlay olamiz

Masalan:

let ids:number[]
ids= [10, 20]
ids.push("30") // error

let arr:(string | number)[]
arr = [10, "Up"]

### INTERFACE

Interfeyslar ob'ektni tasvirlash uchun ishlatiladi.Interfeyslar har doim qayta ochilishi mumkin.

Masalan:

interface person{
name:string
isProgrammer:boolean
}

let p1: person={
name:Abdulloh
isProgrammer:true
}
