# Projeto de Cybersecurity: Ransomware Educacional

Este projeto foi desenvolvido como parte dos estudos me **Cybersecurity** para demonstrar o funcionamento básico de um ransomware. O objetivo é criar um entendimento prático sobre como os ransomware atuam na criptografia e descriptografia de arquivos e reforçar a importância de medidas preventivas contra esse tipo de ameaça. **Este código é estritamente para fins educacionais** e **não deve ser usado de maneira mal-intencionada**.

---

## ⚠️ Aviso Importante
Este código foi criado apenas para o aprendizado e não deve ser usado em ambientes de produção ou fora de um ambiente controlado de testes.

## Descrição do Projeto

O projeto simula o comportamento básico de um ransomware ao criptografar e, em seguida, descriptografar um arquivo de texto simples. A chave de criptografia é usada com o algoritmo **AES (Advanced Encryption Standard)**, permitindo a segurança dos dados criptografados. No exemplo, um arquivo fictício chamado `teste.txt` é criptografado e salvo com uma extensão `.ransomwareteste`. Em seguida, o arquivo é descriptografado, e a versão criptografada é removida do sistema.

## Dependências

O projeto utiliza a biblioteca `pyaes` para realizar a criptografia e descriptografia do conteúdo do arquivo. Certifique-se de instalar o módulo antes de executar o código:

```bash
pip install pyaes
