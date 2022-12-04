# praktikum.7
### Nama : riski probo sadewo
### Nim : 312210191
### Kelas : TI.22.A2
### Tugas Latihan 1
## latihan 1 
### ubahlah kode funsi di bawah ini menggunakan lambda
![gambar](gambar/1.1.png)
### code
'''
# riski probo sadewo
print("________________________________________")
#mengubah function menggunakan lambda
def a(x):
    return x ** 2
lambda x: x ** 2
print("1. Mengubah function menggunakan Lambda \n   def a(x): \n \t   return x ** 2")
print("   Hasil : lambda x: x ** 2")
def b(x, y):
    return math.sqrt(x ** 2 + y ** 2)
lambda x, y: math.sqrt(x ** 2 + y ** 2)
print("________________________________________")
print("2. Mengubah function menggunakan Lambda \n   def b(x, y): \n \t   return math.sqrt(x ** 2 + y ** 2)")
print("   Hasil : lambda x, y: math.sqrt(x ** 2 + y ** 2))")
def c(*args):
    return sum(args) / len(args)
lambda *args: sum(args) / len(args)
print("________________________________________")
print("3. Mengubah function menggunakan Lambda \n   def c(*args): \n \t   return sum(args) / len(args)")
print("   Hasil : lambda *args: sum(args) / len(args))")
def d(s):
    return "".join(set(s))
lambda s: "".join(set(s))
print("________________________________________")
print("4. Mengubah function menggunakan Lambda \n   def d(s): \n \t   return "".join(set(s))")
print("   Hasil : lambda s: "".join(set(s)))")
'''
