# 🔐 Fiap Registro de Usuário API

## 💬 Sobre o Repositório

Este repositório faz parte do projeto de **desenvolvimento de um sistema de gestão unificado para restaurantes**, criado em parceria com estudantes da **FIAP**, como uma **solução colaborativa** voltada à **redução de custos e otimização de processos**.  

O módulo atual fornece a base para **autenticação e gerenciamento de usuários**, permitindo que **clientes e administradores** interajam de forma **segura e integrada** com futuras funcionalidades da plataforma.  

O desenvolvimento segue uma **abordagem por fases**, garantindo:  
- 🧩 Evolução gradual das funcionalidades  
- 🔄 Flexibilidade para ajustes conforme feedback dos restaurantes e clientes  
- 📈 Escalabilidade para suportar novos módulos (pedidos online, avaliações, gestão de cardápio etc.)

---

## ⚙️ Funcionalidades Implementadas

### ✅ **Validação de Login (Obrigatória)**
- Verificação de credenciais de acesso (e-mail e senha)  
- Retorno de mensagens claras em caso de falha  
- Bloqueio de acesso para logins inválidos  
- Integração com as camadas de serviço e tratamento de exceptions  

### 🧪 **Coleção de Testes — Postman**
A coleção Postman em formato JSON cobre os principais cenários da API:  
- 🧾 Cadastro de usuário válido  
- ⚠️ Tentativa de cadastro inválido (e-mail duplicado, campos obrigatórios ausentes)  
- 🔐 Validação de login (obrigatória)  
- 🔄 Alteração de senha (sucesso e erro)  
- ✏️ Atualização de dados do usuário (sucesso e erro)  
- 🔎 Busca de usuários pelo nome  

**Como usar:**  
1. Acesse o repositório raiz: [Fiap Registro de Usuário API](https://github.com/RoAlencar/Fiap_Registra_Usuario?tab=readme-ov-file)  
2. Siga as instruções para rodar o projeto localmente (Java, Spring Boot, Docker, etc.)  
3. Abra o **Postman**  
4. Clique em **Import > File > Upload Files**  
5. Selecione a coleção `Fiap-RegistroUsuario-Collection.json` disponível no repositório  
6. Configure a variável de ambiente: `{{base_url}} = http://localhost:8080`  
7. Execute os testes conforme cada cenário  

---

## 👨‍💻 Autor

**Ademar Mitsuo Kumabe Junior**  
Estudante de **Arquitetura e Desenvolvimento em Java – FIAP**  
📧 [ademar.kumabe@hotmail.com](mailto:ademar.kumabe@hotmail.com)  

---

> 💡 *“Testar é garantir que cada funcionalidade entregue gere confiança, e não apenas código.”*  
> — Ademar Kumabe
