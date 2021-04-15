# Poligono-estrelado Padrao do Triangulo de Estrelas


# ----codescracker.com----

print("Full Pyramid Pattern of Stars (*): ")

for i in range(5):

    for s in range(-6, -i):
    
        print(" ", end="")
        
    for j in range(i+1):
    
        print("* ", end="")
        
    print()
