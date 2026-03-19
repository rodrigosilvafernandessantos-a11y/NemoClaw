| 🧩 Categoria             | ⚙️ Comando                                  | 📌 O que faz                                              |
| ------------------------ | ------------------------------------------- | --------------------------------------------------------- |
| 🚀 Inicializar interface | `openclaw tui`                              | Abre o modo interativo do agente (principal forma de uso) |
| 🔧 Diagnóstico           | `openclaw doctor`                           | Verifica instalação, erros e configuração geral           |
| 🔄 Diagnóstico avançado  | `openclaw doctor --deep`                    | Verificação mais completa (inclui memória, plugins, etc.) |
| 🔁 Reiniciar serviço     | `systemctl --user restart openclaw-gateway` | Reinicia o gateway (muito importante após mudanças)       |
| 📊 Status do gateway     | `systemctl --user status openclaw-gateway`  | Mostra se o bot está rodando corretamente                 |
| 📡 Logs em tempo real    | `journalctl --user -u openclaw-gateway -f`  | Mostra logs ao vivo (essencial para debug)                |

