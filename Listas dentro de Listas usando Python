def linha():
    print('*'*70)

linha()
print('                                LIVROS')
linha()

print('BEM-VINDO(A) À MINHA COLEÇÃO DE LIVROS!\n')
print('LIVROS CADASTRADOS:')

livros = list()
indice = list()
livros.append('')
livros.append('')
livros.append('')
indice.append(livros[:])

livros[0] = 'Dom Casmurro'
livros[1] = 'Ano: 1899'
livros[2] = 'Autor: Machado de Assis'
indice.append(livros[:])

livros[0] = 'Prosopopeia'
livros[1] = 'Ano: 1601'
livros[2] = 'Autor: Bento Teixeira'
indice.append(livros[:])

livros[0] = 'Marília de Dirceu'
livros[1] = 'Ano: 1792'
livros[2] = 'Autor: Tomás Antônio Gonzaga'
indice.append(livros[:])

livros[0] = 'Memórias Póstumas de Brás Cubas'
livros[1] = 'Ano: 1881'
livros[2] = 'Autor: Machado de Assis'
indice.append(livros[:])

livros[0] = 'Canção do Exílio'
livros[1] = 'Ano: 1846'
livros[2] = 'Autor: Gonçalves Dias'
indice.append(livros[:])

livros[0] = 'Triste Fim de Policarpo Quaresma'
livros[1] = 'Ano: 1915'
livros[2] = 'Autor: Lima Barreto'
indice.append(livros[:])

livros[0] = 'Vidas Secas'
livros[1] = 'Ano: 1938'
livros[2] = 'Autor: Graciliano Ramos'
indice.append(livros[:])

livros[0] = 'Eu'
livros[1] = 'Ano: 1912'
livros[2] = 'Autor: Augusto dos Anjos'
indice.append(livros[:])

livros[0] = 'Os Maias'
livros[1] = 'Ano: 1888'
livros[2] = 'Autor: Eça de Queiroz'
indice.append(livros[:])

livros[0] = 'Nature'
livros[1] = 'Ano: 1836'
livros[2] = 'Autor: Ralph Waldo Emerson'
indice.append(livros[:])

for i in indice:
    print(i[0])
    
linha()    
print('                                MENU')
linha()
opcao = 0
while opcao != 4:
    print('''    [ 1 ] Adicionar um livro
    [ 2 ] Apagar um livro
    [ 3 ] Ver detalhes do livro
    [ 4 ] Sair''')
    opcao = int(input('Escolha uma opção: '))

    if opcao==1:
        print('---ADICIONAR UM NOVO LIVRO!---')
        novolivro = input('Nome: ')
        anonovo = str(input('Ano: '))
        anonovo = 'Ano: ' + anonovo
        autornovo = input('Autor: ')
        autornovo = 'Autor: '+ autornovo 
        livros[0] = novolivro
        livros[1] = anonovo
        livros[2] = autornovo
        indice.append(livros[:])
        for i in indice:
            print(i[0])
        linha()    
        print('                                MENU')
        linha()
    
    elif opcao==2:
        print('---APAGAR UM LIVRO DA LISTA!---')
        deletar = int(input('Qual item vc quer deletar da lista? '))
        del indice[deletar]
        for i in indice:
            print(i[0])            
        linha()    
        print('                                MENU')
        linha()
    elif opcao==3:
        print('---VER DETALHES DO LIVRO!---')
        veritem = int(input('Qual item vc gostaria de ver os detalhes? '))
        linha()
        print(indice[veritem])
        linha()
        for i in indice:
            print(i[0])
        linha()    
        print('                                MENU')
        linha()
            
    elif opcao==4:
        print('FIM DO PROGRAMA!! VOLTE SEMPRE!!!')
    else:
        print('OPÇÃO INVÁLIDA! TENTE NOVAMENTE!')
