310 CLS
judul$ = "program Luas Lingkaran"
a = LEN(judul$)
tengah = (80 / 2) - (a / 2)
PRINT STRING$(80, "-")
PRINT TAB(tengah); judul$
PRINT STRING$ (80, "-")
INPUT "Masukan Nilai Jari-Jari Lingkaran : ", r
luas = 22 / 7 * r * r
PRINT "Luas Lingkarannya 	= "; luas; "cm^2"
