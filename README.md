# Phishing para Captura de Senhas do Facebook

## Ferramentas Necessárias
- **Kali Linux**: Sistema operacional projetado para testes de penetração.
- **setoolkit**: Ferramenta integrada ao Kali Linux para simulação de ataques sociais.

---

## Configurando o Phishing no Kali Linux

1. **Acessar como root**:
   Execute o comando abaixo para obter permissão de superusuário:
   ```bash
   sudo su
   ```

2. **Iniciar o setoolkit**:
   Inicie a ferramenta digitando o seguinte comando no terminal:
   ```bash
   setoolkit
   ```

3. **Selecionar o tipo de ataque**:
   Escolha a opção:
   ```
   Social-Engineering Attacks
   ```

4. **Definir o vetor de ataque**:
   Escolha a opção:
   ```
   Web Site Attack Vectors
   ```

5. **Selecionar o método de ataque**:
   Escolha a opção:
   ```
   Credential Harvester Attack Method
   ```

6. **Escolher o método do site clonado**:
   Escolha a opção:
   ```
   Site Cloner
   ```

7. **Obter o endereço IP da máquina**:
   Utilize o comando abaixo para identificar o IP local que será usado no ataque:
   ```bash
   ifconfig
   ```
   Copie o endereço IPv4 exibido na interface de rede em uso.

8. **Inserir a URL a ser clonada**:
   No prompt, insira o link do site alvo:
   ```
   http://www.facebook.com
   ```

---

### Resultados
![image](https://github.com/user-attachments/assets/929586e6-b4af-4ca7-8cd5-d34f38fe4dd0)


> **Nota Importante:** Este procedimento é apresentado exclusivamente para fins educacionais e de conscientização sobre segurança. O uso de phishing para qualquer propósito mal-intencionado é ilegal e pode levar a graves conseqüências legais.



