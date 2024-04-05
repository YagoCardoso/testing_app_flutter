# Testing App flutter




---------------------------
# Testes Unitarios (TDD)

- Para Testar a inclusao e remoçao do item na lista de favoritos: flutter test test/models/favorites_test.dart


- Dica: é possível fazer todos os testes no diretório test de uma só vez. Basta executar:  flutter test
   


# Testes de Widgets

- Para testar os widgets da Home,  verificar se o listView apareceu e testar o scrolling: flutter test test/home_test.dart

- Para tertar utilizandon um Device fisico ou um emulador: flutter run test/home_test.dart



# Testes de Integraçao

- Para rodar o teste de integraçao, garante que o emulador esta configurado ou use um device fisico
- Use esse comando para rodar o teste de integraçao que foi criado em integration_test/app.test.dart: flutter integration_test/app.test.dart


