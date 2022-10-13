# My-First-Project
## This code allows to find for which amino-acid each codon codifies for
### Biology

Code:
`
x = (["Fenilanlina" , "Leucina", "Isoleucina", "Metionina", "Valina", "Serina", "Prolina", "Treonina", "Alanina", "Tirosina", "Stop", "Histidina", "Glutamina", "Asparagina", "Lisina"])

Letras= True

while Letras==True:
  AminoName = str(input("Introduzca el codon del cual quiere conocer el nombre del aminoácido: "))
  y = AminoName.upper()
  w= len(AminoName)
  if y == "UUU" or y == "UUC":
    print("\n",y,"=", x[0],"\n")
  elif w!=3 and y!="STOP":
    print("\n", "Recuerda que un aminoácido se compone de tres nucleotidos, Intentalo de nuevo", "\n")
  elif y == "UUA" or y == "UUG" or y == "CUU" or y == "CUC" or y == "CUA" or y == "CUG":
    print("\n",y, "=", x[1],"\n")
  elif y == "AUU" or y == "AUC" or y == "AUA":
      print("\n",y, "=", x[2],"\n")
  elif y == "AUG":
    print("\n",y, "=", x[3],"\n")
  elif y == "GUU" or y == "GUC" or y == "GUA" or y == "GUG":
    print("\n",y, "=", x[4],"\n")
  elif y == "UCU" or y == "UCC" or y == "UCA" or y == "UCG":
    print("\n",y, "=", x[5],"\n")
  elif y == "CCU" or y == "CCC" or y == "CCA" or y == "CCG":
    print("\n",y, "=", x[6],"\n")
  elif y == "ACU" or y == "ACC" or y == "ACA" or y == "ACG":
    print("\n",y, "=", x[7],"\n")
  elif y == "GCU" or y == "GCC" or y == "GCA" or y == "GCG":
    print("\n",y, "=", x[8],"\n")
  elif y == "UAU" or y == "UAC":
    print("\n",y, "=", x[9],"\n")
  elif y == "UAA" or y == "UAG" or y == "UGA":
    print("\n",y, "=", x[10],"\n")
  elif y == "CAU" or y == "CAC":
    print("\n",y, "=", x[11],"\n")
  elif y == "CAA" or y == "CAG":
    print("\n",y, "=", x[12],"\n")
  elif y == "AAU" or y == "AAC":
    print("\n",y, "=", x[13],"\n")
  elif y == "AAA" or y == "AAG":
    print("\n",y, "=", x[14],"\n")  
  elif y=="STOP":
    Letras=False 
  else: 
    print("\n", "Recuerda que el ARN solo puede tener Adenina (A), Citosina (C), Guanina (G), y Uracilo (U), Intentalo de nuevo", "\n")
  `
