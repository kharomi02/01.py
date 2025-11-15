# 01.py
code penilaian rata rata grade keterangan lulus dan tidak lulus 

    while True:
    
    print("====sistem penilaian mahasiswa====")
    nama = input("masukan nama : ")
    tugas = int(input("tugas : "))
    kuis = int(input("kuis : "))
    uts = int(input("uts : "))
    uas = int(input("uas : "))
    
    rata_rata = (tugas + kuis + uts + uas)/ 4
    print("nama : ", nama)
    print("nilai Rata-rata : ", rata_rata)

    if rata_rata>= 85:
       print("grade : A")
    elif rata_rata >=  70:
        print("grade : B")
    elif rata_rata >= 55:
        print("grade : C")
    elif rata_rata >= 45:
        print("grade : D")
    else :
        print("grade : E")

    
    if rata_rata > 55:
        print("lulus")
    else:
        print("tidak lulus")

    ulang = input("apakah anda ingin mengulang program? (YA/TIDAK): ")
    if ulang != 'ya':
        print("===program selesai. syukron===")
        break
