def Perkenalan():
    def kata_kata():
        var = ["Fasuyaaa", "Github", "Kali-Linux", "kegabutan", "sumber", "Linux"]
        sosmed = ["@fasuyaaa","@vinfasss","VINZ XD"]
        negara = "Indonesia"
        kota = "Semarang"
        data = "BIODATA"
        bio = ["Fasuyaaa", int((36*3-84)-(69/(11*2+1)*3)), "X PPLG 2", "12 APRIL", int((2022-100)+85), "NETWORKING"]
        print ("""


█▀▀ ▄▀█ █▀ █░█ █▄█ ▄▀█ ▄▀█ ▄▀█
█▀░ █▀█ ▄█ █▄█ ░█░ █▀█ █▀█ █▀█


Halo semuanya, saya {0} dari {10}, {9}. Di {1} saya sebenarnya hanya berisi hasil dari {3} saya jadi jangan terlalu berharap banyak hehehehe.
Tidak semua yang ada disini murni hasil saya, karena ada mungkin beberapa hasil pengembangan dari beberapa {4}. Saya menggunakan OS distribusi dari {5} yaitu {2}.
\n

       {17}            
_________________________
          *
 Username : {11}         
 Age      : {12}         
 Class    : {13}         
 Date     : {14} {15}    
 Field    : {16}         
__________*______________
            """.format(var[0],var[1],var[2],var[3],var[4],var[5],sosmed[0],sosmed[1],sosmed[2],negara,kota,bio[0],bio[1],bio[2],bio[3],bio[4],bio[5],data))

    def b_program():
        bahasa = ["py","js","php"]
        bahasa[0] = "Python"
        bahasa[1] = "JavaScript"
        bahasa[2] = "Hypertext Preprocessor"
    
        if bahasa == "html" or bahasa == "css":
            print ("""
  BAHASA PROGRAM          
_____________________
        *
  TRUE OR FALSE?    
  =   FALSE    =
________*____________                  
                   """)
        
        elif bahasa == "html" and bahasa == "css":
            print ("""
  BAHASA PROGRAM          
_____________________
        *
  TRUE OR FALSE?    
  =   FALSE    =
________*____________                  
                   """)
        
        elif not bahasa == ["Python", "JavaScript", "Hypertext Preprocessor"]:
            print ("""
  BAHASA PROGRAM          
_____________________
        *
  TRUE OR FALSE?    
  =   FALSE    =
________*____________                  
                   """)
        
        elif not bahasa == "html" and bahasa == "css":
            print ("""
  BAHASA PROGRAM          
_____________________
        *
  TRUE OR FALSE?    
  =   TRUE    =
________*____________                  
                   """)
        
        elif not bahasa == "html" or bahasa == "css":
            print ("""
  BAHASA PROGRAM          
_____________________
        *
  TRUE OR FALSE?    
  =   TRUE    =
________*____________                  
                   """)
    
        elif bahasa == ["Python", "JavaScript", "Hypertext Preprocessor"]:
            print ("""
  BAHASA PROGRAM          
_____________________
        *
  TRUE OR FALSE?    
  =   TRUE    =
________*____________                  
                   """)
         
    def OS():
        LINUX_Distro = ["Linux Mint", "Ubuntu", "MX Linux", "Fendora", "Debian", "Kali", "Elementary OS", "Zorin", "CentOS", "SteamOS"]
        Windows_V = ["1","2","3","3.1","95","98","Me","XP","Vista","7","8","8.1","10","11"]
        Mac_OS = ["Cheetah","Puma","Jaguar","Panther","Tiger","Leopard","Snow Leopard","Lion","Mountain Lion","Mavericks","Yosemite","El Capitan","Sierra","High Sierra","Mojave","Catalina","Big Sur","Monterey","Ventura"]
        Mac_OS = Mac_OS + ["-"]
        
        print ("""

       OS USE            
_________________________
          *
Linux     : {0} Linux        
Windows   : {1}         
Mac OS    : {2}              
__________*______________
               """.format(LINUX_Distro[5],Windows_V[13],Mac_OS[19]))
        
             
            
    kata_kata()
    print("\n")
    b_program()
    OS()  
     
Perkenalan()
