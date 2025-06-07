# 🔐 SSL/TLS - Segurança na Comunicação Digital

## O que é SSL/TLS?
- **SSL (Secure Sockets Layer)**: protocolo original de segurança.
- **TLS (Transport Layer Security)**: versão mais segura e moderna.
- Ambos garantem **criptografia** e **autenticação** entre cliente e servidor.

---

## ⚙️ Principais Funções

| Função              | Descrição                                              |
|---------------------|--------------------------------------------------------|
| Confidencialidade | Protege os dados durante a transmissão com criptografia |
| Integridade       | Garante que os dados não foram alterados               |
| Autenticação      | Verifica a identidade do servidor                      |

---

## 🤝 Como Funciona o Handshake

1. Cliente envia “Hello” com versões e algoritmos suportados
2. Servidor responde com certificado e algoritmo escolhido
3. Cliente valida certificado e gera chave de sessão
4. Ambos estabelecem canal criptografado

### Exemplo visual:
![Handshake SSL/TLS](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*FV5F1zGU9zrMKTHkRRqX1g.png)

---

## 📅 Evolução das Versões

| Versão       | Estado       | Observações                          |
|--------------|--------------|--------------------------------------|
| SSL 2.0/3.0  | ❌ Obsoleto   | Vulnerável e descontinuado           |
| TLS 1.0/1.1  | ⚠️ Inseguro   | Inadequado para uso atual            |
| TLS 1.2      | ✅ Estável    | Amplamente utilizado atualmente      |
| TLS 1.3      | 🚀 Atual      | Mais rápido e seguro                 |

---

## Como identificar uma conexão segura

| HTTPS (Seguro)                                   | HTTP (Inseguro)                                   |
|--------------------------------------------------|---------------------------------------------------|
| Cadeado na barra de endereços                    |  Aviso de “Não seguro”                          |
| URL começa com `https://`                        | URL começa com `http://`                          |
| Certificado digital válido e confiável           | Dados transmitidos sem criptografia              |

---

## 💡 Importância

- **Transações Financeiras**: Protege dados bancários e de cartão.
- **Senhas e Login**: Garante segurança no acesso a contas.
- **Dados Pessoais**: Protege privacidade e identidade.
- **E-commerce**: Essencial para segurança em compras online.

---

## ✅ Conclusão

- SSL/TLS é essencial para garantir **segurança, confiança e privacidade**.
- Protege contra **interceptações, ataques man-in-the-middle e fraudes**.
- Sempre verifique o **cadeado 🔒** antes de inserir informações sensíveis.

---

## Feito por:

- João Pedro Balduino  
- Enzo Santos  
- José Alves  

---

## 🔗 Fontes e referências visuais

- [🔗 Cloudflare - How TLS Works](https://www.cloudflare.com/learning/ssl/what-is-ssl/)  
- [🔗 Medium - TLS Handshake Explained](https://medium.com/@koushik.sivaraman/tls-handshake-a-pictorial-guide-e6e2f2f08b8c)  
- [🔗 Mozilla - Transport Layer Security (TLS)](https://developer.mozilla.org/en-US/docs/Web/Security/Transport_Layer_Security)
