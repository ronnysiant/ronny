# Algoritma Pertemuan 2
hei guys!! kali oini saya akan memberikan beberapa tips atau tutorial bagaimana proses pembuatan coding atau program sederhana mengenai cara kerja pada logaritma, maaf aja nih kalo tutorialnya sedikit ngebosenin tapi next time akan aku bikin semenarik mungkin sehingga kita semua bisa belajar bareng bikin coding. pantau aja terus chanel ini karena disini kalian bisa menambah wawasan seputar dunia informatika.

# mencetak bilangan terbesar dari 3 buah bilangan
B1=int(input("Bilangan Pertama : "))
B2=int(input("Bilangan Kedua   : "))
B3=int(input("Bilangan Ketiga  : "))
print("bilangan terbesar adalah ",end="")
if B1>B2:
    if B1>B3:
        print(B1)
    else:
        print(B3)
elif B2>B3:
    print(B2)
else:
    print(B3)
