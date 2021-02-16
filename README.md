# API-Carros
Api publica de consulta de placas.

BD ATUAL | 184277666  | de placas

OBS: V1 DESATIVADA PARCIALMENTE.

OBS RETORNO EM XML SERÁ DESATIVADO EM BREVE
quem tiver interesse em continuar usando a api entre em contato.

https://app.swaggerhub.com/apis/douglasrc/api-carros/1.0.1#/


exemplo de consulta xml
https://apicarros.com/v1/consulta/atj8617
retorno
```
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
    <soap:Body>
        <ns2:getStatusResponse xmlns:ns2="http://soap.br/">
            <return>
                <codigoRetorno>0</codigoRetorno>
                <mensagemRetorno>Sem erros.</mensagemRetorno>
                <codigoSituacao>0</codigoSituacao>
                <situacao>Sem restrição</situacao>
                <modelo>HONDA/CG150 FAN ESDI</modelo>
                <marca>HONDA/CG150 FAN ESDI</marca>
                <cor>Vermelha</cor>
                <ano>2010</ano>
                <anoModelo>2011</anoModelo>
                <placa>ATJ8617</placa>
                <data>30/08/2018 às 14:19:37</data>
                <uf>PR</uf>
                <municipio>APUCARANA</municipio>
                <chassi>01542</chassi>
                <dataAtualizacaoCaracteristicasVeiculo>None</dataAtualizacaoCaracteristicasVeiculo>
                <dataAtualizacaoRouboFurto>None</dataAtualizacaoRouboFurto>
                <dataAtualizacaoAlarme>None</dataAtualizacaoAlarme>
            </return>
        </ns2:getStatusResponse>
    </soap:Body>
</soap:Envelope>

```
exemplo de consulta json
https://apicarros.com/v1/consulta/atj8617/json
```
{
  "ano": "2010", 
  "anoModelo": "2011", 
  "chassi": "01542", 
  "codigoRetorno": "0", 
  "codigoSituacao": "0", 
  "cor": "Vermelha", 
  "data": "30/08/2018 \u00e0s 14:19:37", 
  "dataAtualizacaoAlarme": null, 
  "dataAtualizacaoCaracteristicasVeiculo": null, 
  "dataAtualizacaoRouboFurto": null, 
  "marca": "HONDA/CG150 FAN ESDI", 
  "mensagemRetorno": "Sem erros.", 
  "modelo": "HONDA/CG150 FAN ESDI", 
  "municipio": "APUCARANA", 
  "placa": "ATJ8617", 
  "situacao": "Sem restri\u00e7\u00e3o", 
  "uf": "PR"
}
```

V2 
```
{
  "codigoRetorno": "0",
  "mensagemRetorno": "Sem erros.",
  "codigoSituacao": "0",
  "situacao": "Sem restrição",
  "chassi": "*****01542",
  "modelo": "HONDA/CG150 FAN ESDI",
  "marca": "HONDA/CG150 FAN ESDI",
  "cor": "Vermelha",
  "ano": "2011",
  "anoModelo": "2011",
  "placa": "ATJ8617",
  "data": "16/02/2021 10:27:21",
  "municipio": "Apucarana",
  "uf": "PR",
  "dataAtualizacaoCaracteristicasVeiculo": "16/02/2021",
  "dataAtualizacaoRouboFurto": "16/02/2021",
  "dataAtualizacaoAlarme": "16/02/2021",
  "extra": {
    "id": "",
    "data_atualiacao": "",
    "chassi": "CHASSICOMPLETO",
    "placa": "ATJ8617",
    "faturado": "",
    "ano_fabricacao": "2010",
    "municipio": {
      "municipio": "APUCARANA",
      "uf": "PR"
    },
    "uf_placa": "PR",
    "marca_modelo": {
      "modelo": "HONDA/CG150 FAN ESDI",
      "marca": "HONDA",
      "segmento": "Moto",
      "sub_segmento": "CITY",
      "grupo": "CG150",
      "version": null
    },
    "combustivel": {
      "combustivel": "Alcool / Gasolina"
    },
    "potencia": "0",
    "capacidade_carga": "0",
    "nacionalidade": {
      "nacionalidade": "Nacional"
    },
    "linha": "",
    "carroceria": "",
    "caixa_cambio": "",
    "eixo_traseiro_dif": "",
    "terceiro_eixo": "",
    "motor": "NUMERACAO MOTOR COMPLETA",
    "tipo_doc_faturado": {
      "tipo_pessoa": "Juridica"
    },
    "uf_faturado": "PR",
    "tipo_doc_prop": {
      "tipo_pessoa": "Fisica"
    },
    "ano_modelo": "2011",
    "tipo_veiculo": {
      "tipo_veiculo": "Motocicleta"
    },
    "especie_veiculo": "1",
    "tipo_carroceria": {
      "carroceria": "NAO APLICAVEL"
    },
    "cor_veiculo": {
      "cor": "Vermelha"
    },
    "quantidade_passageiro": "2",
    "situacao_chassi": "N",
    "eixos": "0",
    "tipo_montagem": "1",
    "tipo_doc_importadora": "",
    "ident_importadora": "",
    "di": "0",
    "registro_di": "",
    "unidade_local_srf": "0000000",
    "ultima_atualizacao": "",
    "restricao_1": "3",
    "restricao_2": "0",
    "restricao_3": "0",
    "restricao_4": "0",
    "limite_restricao_trib": "",
    "cilindradas": "149",
    "cap_maxima_tracao": "0",
    "peso_bruto_total": "30",
    "situacao_veiculo": "S",
    "placa_modelo_antigo": "ATJ8617",
    "placa_modelo_novo": "ATJ8G17",
    "placa_nova": "f"
  }
}
```
