# labpy1
Menentukan bilangan terbesar dari tiga buah bilangan yang di inputkan dari keyboard

Background tampilan awal

    print (' _________________________________ ')
    print ('|                                 |')
    print ('|PROGRAM MENCARI BILANGAN TERBESAR|')
    print ('|_________________________________|')
    print ('                                   ')

1.Mendefinisikan perulangan dengan mengetikkan;

    def pengulangan():

2.Memasukkan 3 bilangan yang anda inginkan ;

    print ('Masukkan 3 bilangan yang diinginkan!')
    a=int(input('Bilangan Pertama : '))
    b=int(input('Bilangan Kedua   : '))
    c=int(input('Bilangan Ketiga  : '))

3.Membandingkan nilai a,b,c dengan rumus if ;

    if a>b:
        if a>c:
            print ('Bilangan terbesarnya adalah :',a)
        else:
            print ('Bilangan terbesarnya adalah :',c)
    else:
        if b>c:
            print ('Bilangan terbesarnya adalah :',b)
        else:
            print ('Bilangan terbesarnya adalah :',c)
            
4.Pilihan apa ingin mencoba lagi atau tidak;

    print ('')
    print ('Ingin coba lagi? (Y/T)')
    x=input()
    if x=='Y':
        return pengulangan()
    if x=='T':
        print('Terimakasih telah menggunakan program ini.')

5.Jangan lupa ketikkan "pengulangan()" ,
 apabila lupa mengetikkan kata tersebut 
 maka definisi perulangan tidak akan muncul pada saat program dijalankan.
 
