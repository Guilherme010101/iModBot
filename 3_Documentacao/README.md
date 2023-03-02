
# Documentação

Nesta pasta pode encontrar documentação para varios aspetos do projeto. Existem dois ficheiro de cada documento, um para pdf e o outro para word. Para indentificá-los, os ficheiros pdf têm a palavra "Novo" antes do nome de cada documento.

- **3-01_iModBot_Tech_Manual.docx** ou **Novo_3-01_iModBot_Tech_Manual.pdf**
  - Descreve os componentes utilizados no projeto, as funções proporcionadas pela biblioteca entre outros aspetos.

- **3-02_iModBot_Assembly_And_Software_Installation_Tutorial.docx** ou **Novo_3-02_iModBot_Assembly_And_Software_Installation_Tutorial.pdf**
  - Explica como montar o robô, instalar os seus softwares e a programação e instalação dos mesmos.

- **3-03_iModBot_Offline_Assembly_Guide.docx** ou **Novo_3-03_iModBot_Offline_Assembly_Guide.pdf**
  - Fornece uma lista de componentes e apresenta as ligações que devem ser efetuadas entre os componentes.

- **3-04_Add_ESP32_Arduino_IDE.docx** ou **Novo_3-04_Add_ESP32_Arduino_IDE.pdf**
  - Explica como conectar a placa de desenvolvimento ESP32 ao software Arduino IDE.
  
- **3-05_Add_ArduBlock_Arduino_IDE.docx** ou **Novo_3-05_Add_ArduBlock_Arduino_IDE.pdf**
  - Explica como instalar o ArduBlock no software Arduino IDE.
  
- **3.3_Como_instalar_bibliotecas_no_Arduino_IDE.pdf**
  - Explica como instalar biblioteacas no software Arduino IDE.
  
  
- **3.6_iModRob_Eagle_2_layer_board.zip**
  - Também é disponibilizado o projeto para a aplicação Autodesk Eagle que contém uma placa de circuito impresso (PCB) que facilitará a montagem dos componentes no robô.

# Esquema eletrónico e PCB


  - Foram inseridos vários pontos de teste na placa de circuito impresso. 
  - Foram adicionados jumpers para poder desconectar a alimentação geral do circuito e/ou a alimentação da placa de desenvolvimento DOIT ESP32 Devkit V1 e/ou a alimentação do módulo baseado no integrado L293D.

**Esquema eletrónico**:

 <p align="center">
  <img width="882" height="466" src="https://user-images.githubusercontent.com/60508542/87034511-d5f9b100-c1df-11ea-8ed3-99767a2c4866.png">
</p>


**Placa de circuito impresso** (sem o plano de massa visível):

 <p align="center">
  <img width="768" height="798" src="https://user-images.githubusercontent.com/60508542/87034508-d4c88400-c1df-11ea-97bc-7f3ebd613b46.png">
</p>


    Uma boa opção para conectar/desconectar a alimentação seria o uso de conectores "jumper two pins".
    
 <p align="center">
  <img width="250" height="250" src="https://cdn-media.itead.cc/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/i/m/im120707001_6.jpg">
</p>
