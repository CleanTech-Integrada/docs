---
description: Estrutura e arquitetura da aplicação.
---

# 🏗 Aplicação

Para realizar o MVP da aplicação começamos com uma estrutura simples, desacoplada e reutilizável do sistema, onde temos uma aplicação em Laravel responsável por receber os inputs do usuário e enviar esses dados para uma API rest em Django que é responsável por comunicar com o modelo de inteligência artificial e retornar para a aplicação Laravel um resultado visível para o usuário.

<figure><img src=".gitbook/assets/arch ia.png" alt="" width="310"><figcaption><p>Arquitetura do sistema.</p></figcaption></figure>

No diagrama acima temos um detalhe de banco de dados... decidimos centralizar os dados consumidos pelas aplicações para facilitar a gerencia de recursos entre elas.

{% hint style="info" %}
No projeto foi utilizado o PostgreSQL para banco de dados.
{% endhint %}
