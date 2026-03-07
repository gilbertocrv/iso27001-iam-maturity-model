# Modelo de Maturidade em Gestão de Acessos (ISO 27001 + LGPD)

🔗 **Acesse o projeto:** https://gilbertocrv.github.io/iam-maturity-iso27001/

Desenvolvi um formulário prático para avaliar a maturidade de controles de Access Management, baseado nas normas públicas ISO/IEC 27001:2022 e ISO 27701.

---

## Controles Avaliados

| Controle | Nome | Camada | Link |
|---|---|---|---|
| 5.15 | Access Control | Autorização | [Deep Dive](https://gilbertocrv.github.io/access-management-maturity-iso27001/) |
| 5.16 | Identity Management | Identidade | [Deep Dive](https://gilbertocrv.github.io/identity-management-maturity-iso27001-5-16/) |
| 5.17 | Authentication Information | Autenticação | [Deep Dive](https://gilbertocrv.github.io/authentication-information-maturity-iso27001-5-17-/) |
| 5.18 | Access Rights | Autorização | [Deep Dive](https://gilbertocrv.github.io/identity-management-maturity-iso27001-5-18/) |
| 8.2 | Privileged Access Rights | Privilégio | [Deep Dive](https://gilbertocrv.github.io/identity-management-maturity-iso27001-8-2) | 
| 8.3 | Information Access Restriction | Privilégio | Em breve |
| 8.5 | Secure Authentication | Autenticação | Em breve |

---

## Arquitetura de Controles

```
Identidade → Autenticação → Autorização → Privilégio
  5.16          5.17 · 8.5     5.15 · 5.18    8.2 · 8.3
```

Cada camada depende da anterior. Governança sem enforcement técnico é política sem garantia.

---

## Propósito de Cada Controle

- **5.15 – Access Control:** Define políticas de controle de acesso e restrições.
- **5.16 – Identity Management:** Gestão do ciclo de vida de identidades de usuários.
- **5.17 – Authentication Information:** Proteção e gerenciamento de credenciais.
- **5.18 – Access Rights:** Governança da concessão e revisão de permissões.
- **8.2 – Privileged Access Rights:** Administração de contas e privilégios críticos.
- **8.3 – Information Access Restriction:** Restrição de acesso a informações sensíveis.
- **8.5 – Secure Authentication:** Implementação de autenticação robusta e mecanismos de MFA.

---

## Escala de Maturidade (0–5)

| Nível | Nome | Descrição |
|---|---|---|
| 0 | Inexistente | Controle não existe ou não é aplicado |
| 1 | Ad-hoc | Implementação informal ou isolada |
| 2 | Documentado | Procedimentos registrados, mas ainda não padronizados |
| 3 | Padronizado | Processos aplicados de forma consistente |
| 4 | Automatizado | Controles suportados por ferramentas ou processos automáticos |
| 5 | Baseado em Risco | Decisões e processos alinhados à análise de risco e prioridades de negócio |

---

## Sobre o Projeto

Projeto de estudo e prática desenvolvido de forma independente, baseado nas normas públicas ISO/IEC 27001:2022 e ISO/IEC 27701, com relação aos princípios de proteção de dados da LGPD.

O objetivo é explorar, de forma educacional, conceitos de gestão de identidades, controle de acessos e maturidade de processos, utilizando exemplos práticos e avaliações estruturadas.

O material documenta a evolução da análise de controles de acesso sob a perspectiva de governança, risco e conformidade, mantendo caráter técnico e sem referência a ambientes ou processos corporativos específicos.

---

## Autor

**Gilberto Gonçalves dos Santos Filho**  
Analista de Governança de Identidades — IAM · PAM · GRC  
[LinkedIn](https://linkedin.com/in/gilberto-filho-4430a3184) · [GitHub](https://github.com/gilbertocrv)
