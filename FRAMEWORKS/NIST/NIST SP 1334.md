REDUÇÃO DOS RISCOS DE CIBERSEGURANÇA DE SUPORTES DE ARMAZENAMENTO PORTÁTEIS EM AMBIENTES OT (Resumo NIST SP 1334)
=========================================================================================

Este documento do NIST SP 1334 oferece orientações para **minimizar riscos** ligados ao uso de dispositivos de armazenamento portáteis (USB, discos externos, CDs/DVDs) em ambientes de Tecnologia Operacional (OT).

**Contexto e importância**
--------------------------
Os suportes portáteis são usados para:
- Atualizar firmware em dispositivos isolados
- Recuperar logs para diagnósticos externos
- Transferir dados entre sistemas isolados

Contudo, representam **riscos de cibersegurança** elevados, exigindo controlos específicos.

**Controlos procedimentais**
----------------------------
As organizações devem:
- Gerir dispositivos: aquisição, autorização e gestão dos ativos
- Preferir dispositivos encriptados por hardware (FIPS)
- Restringir uso: apenas quando autorizado
- Criar procedimentos para: aprovisionamento, uso, armazenamento, sanitização e destruição
- Assegurar rastreabilidade: registo de logs (utilizador, n.º de série, data/hora)
- Formar os utilizadores sobre políticas e procedimentos

**Controlos físicos**
---------------------
- Armazenamento seguro em locais restritos
- Inventário e rotulagem (incluindo:
    - autorizados a utilizar
    - redes/sistemas de uso permitido
    - finalidade de utilização)

**Controlos técnicos**
----------------------
- Desativação de portas (via BIOS/SO ou bloqueio físico)
- Restrição por allowlisting de dispositivos
- Análise por antivírus antes e após uso
- Reformatação para reutilização entre equipamentos
- Proteção contra escrita (uso só de leitura)
- Desativação do Autorun
- Encriptação conforme FIPS
- Alertas de atividade e logging de inserção/cópia de dados

**Transporte e sanitização**
----------------------------
- Encriptação ou contentor físico seguro durante transporte
- Verificação de integridade (hash/checksum) em transferências entre entidades
- Sanitização antes do descarte/remoção, com registo e aprovação formal

**Conclusão**
-------------
A combinação de controlos físicos, técnicos e formação reduz significativamente os riscos. Consulte também os documentos NIST SP 800-82 Rev. 3, NIST SP 800-53 Rev. 5 e NIST SP 800-88 Rev. 2 para mais detalhe.

[1](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.1334.pdf)
