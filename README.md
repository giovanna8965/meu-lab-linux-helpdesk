# meu-lab-linux-helpdesk
Laboratório prático de Linux focado em Help Desk: resolvendo conflitos de hardware e otimização de VMs.

📋 Especificações da Máquina Virtual
Sistema Operacional: Ubuntu 24.04 (64-bit).

Memória Base (RAM): 1024 MB (Ajustada para garantir a estabilidade do sistema hospedeiro).

Processadores: 1 CPU.

Armazenamento: 25,00 GB (Disco VDI dinamicamente alocado).

Memória de Vídeo: 128 MB (Aumentada para permitir o carregamento da interface gráfica).

🚀 Desafios Superados (Troubleshooting)
1. Conflito de Alocação de Memória
Durante a configuração inicial, o VirtualBox detectou que mais de 75% da RAM do hospedeiro estava sendo solicitada pela VM.

Solução: Reduzi a memória da VM de 2048 MB para 1024 MB para evitar o congelamento do Windows.

2. Erro de Carregamento Gráfico (Cursor "X")
A máquina virtual ficava travada em uma tela preta com um cursor em formato de "X".

Causa: Memória de vídeo insuficiente (16 MB) para a interface do Ubuntu.

Solução: Aumentei a memória de vídeo para 128 MB nas configurações de Monitor do VirtualBox.
