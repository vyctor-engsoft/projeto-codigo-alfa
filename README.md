#Python
#criar uma lista que informe nome , nota1 , nota2
#tenha variaveis como : turma1 , MEDIA , NOTA1 , NOTA2 , ALUNO
#pergunte o nome do aluno , a nota numero 1 e a nota numero 2
#contenha: PRINT('\N BOLETIM FINAL : ')
#for aluno in turma1 :
#media = (aluno [1] + aluno [2]) /2
turma1 = []

for i in range(1):
    
    nome = input('Qual e o seu nome ?: ')
    nota1 =float(input('NOTA 1: '))
    nota2 =float(input('NOTA 2: '))
    turma1.append([nome , nota1 ,nota2])

print('\n ===[ BOLETIM FINAL ] : ')
for aluno in turma1:
    media = (aluno [1] + aluno[2]) /2
print(f' Aluno ; {aluno [0]} !|! Media:{media: 2f}')
