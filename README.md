# Validado-a-senha.
Validado a senha.


### Password Checker
- Pessa para o usuário um input com a senha e um input com a confirmação de senha
- Para validar a senha, verifique que:
    - A senha e confirmação são iguais
    - A senha possua mais de 8 caracteres
    - A senha tenha letras e números
 
      senha = input("Senha")
confirmacao_senha = input("Confirmação de Senha")

if senha != confirmacao_senha:
    print("Senha e Confirmação são diferentes")
else:
    if senha.isnumeric() or senha.isalpha():
        print("Sua senha precisa ter letras e números")
    else:
        if len(senha) < 8:
            print("Sua senha precisa ter pelo menos 8 caracteres")
        else:
            print("Senha salva com sucesso")
