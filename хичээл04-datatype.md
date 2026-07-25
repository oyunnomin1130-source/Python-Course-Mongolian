# Хичээл 04 — Data Types (Өгөгдлийн төрөл)
Энэ хичээлээр Python хэлний өгөгдлийн төрөл, төрөл бүрийн онцлог, хөрвүүлэлт (typecasting), арифметик үйлдлүүдийг судална.
## Өгөгдлийн төрөл гэж юу вэ?
Python-д өгөгдлийн төрөл нь хувьсагч ямар төрлийн утга хадгалж байгааг илэрхийлдэг.
## Тоон өгөгдөл (Numeric Types)
int — бүхэл тоо

float — бутархай тоо

complex — комплекс тоо (жишээ: 89 + 7j)

## Текстэн өгөгдөл (String)
str — текст, үсэг, өгүүлбэр

## Логик өгөгдөл (Boolean)
bool — True / False

## Дараалсан өгөгдөл (Sequence Types)
list
tuple
set
# Жишээ код
a = '56'          # string

b = 67.34         # float

c = [67,56,9,6,-7]# list

e = 89 + 7j       # complex

d = "Nomin"       # string

d1 = "bol mongol" # string



print("a + b =", int(a) + b)

print(d + str(b))

print(type(a))  # <class 'str'>

print(type(b))  # <class 'float'>

print(type(c))  # <class 'list'>

print(type(d))  # <class 'str'>

print(type(e))  # <class 'complex'>


