# Desafio sobre Backend Skills

 O JSON Web Token (JWT) é um padrão aberto (RFC 7519) que define uma maneira compacta e 
 independente de transmitir com segurança informações entre as partes como um objeto JSON. 
 Essas informações podem ser verificadas e confiáveis ​​porque são assinadas digitalmente. 
 As JWTs podem ser assinadas usando um segredo (com o algoritmo HMAC) ou um par de chaves 
 pública / privada usando RSA ou ECDSA. 
 
 Complete a função create_token para retornar um json web token, gerado usando o algoritmo HS256, que contenha a seguinte informação **{"language": "Python"}**,
 com a palavra secreta **acelera**.
 Complete a função verify_signature para decifrar as informações tratando a exceção de quando a assinatura for inválida devendo retornar o seguinte dicionário **{"error": 2}**.
 Não havendo erro, retornar a informação decifrada.

