# 0.-zadaca
Nulta domaća zadaća

# JMBAG
0036476772

# Pitanje 1:
Nakon što sam dodao referencu, pojavile su se još dvije datoteke: ClassLibrary1.dll i ClassLibrary1 koja je Program Debug Database. Kad maknem .dll datoteku, tad se .exe datoteka ne može pokrenuti nego se javlja FileNotFoundException, zato jer ne može dohvatiti klasu MyConsole koja se inače nalazila u tom .dll-u.
Ako me tražite da vam pošaljem aplikaciju, poslao bih vam dvije datoteke: KonzolnaAplikacija.exe i ClassLibrary1.dll.

# Pitanje 2:
Koristila se stara verzija teksta, zato što konzolna aplikacija prihvaća podatke iz biblioteka koje su već prevedene.

# Pitanje 3:
Pero: Hello World

# Pitanje 4:
PeroClassLibrary.dll se kopirao u Bin/Debug repozitorij.

# Pitanje 5:
Aplikacija i build i dalje rade zato jer se sad referencira kopija .dll-a koja se nalazi u Bin/Debug repozitoriju. PeroClassLibrary se sada traži u projektu KonzolnaAplikacija.
