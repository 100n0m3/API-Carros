# API-Carros
Api publica de consulta de placas.

BD ATUAL | 178383077  | de placas

OBS: V1 DESATIVADA PARCIALMENTE.
quem tiver interesse em continuar usando a api entre em contato vamos gerar um token de acesso!.

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
