# Testing App flutter




---------------------------
# Testes Unitarios (TDD)

![Captura de Tela 2024-04-04 às 23 25 59](https://github.com/YagoCardoso/testing_app_flutter/assets/48061155/8d9a0323-bb98-4669-bc9b-926eebf62ca5)

- Para Testar a inclusao e remoçao do item na lista de favoritos: flutter test test/models/favorites_test.dart


- Dica: é possível fazer todos os testes no diretório test de uma só vez. Basta executar:  flutter test
   


# Testes de Widgets


https://github.com/YagoCardoso/testing_app_flutter/assets/48061155/9526b974-5948-4232-826f-967d826afedb



- Para testar os widgets da Home,  verificar se o listView apareceu e testar o scrolling: flutter test test/home_test.dart

- Para tertar utilizandon um Device fisico ou um emulador: flutter run test/home_test.dart



# Testes de Integraçao



https://github.com/YagoCardoso/testing_app_flutter/assets/48061155/8316ef29-a038-42cf-8b1b-ccebb9d3fcc1



- Para rodar o teste de integraçao, garante que o emulador esta configurado ou use um device fisico
- Use esse comando para rodar o teste de integraçao que foi criado em integration_test/app.test.dart: flutter integration_test/app.test.dart


