# Precifica Shopee

Calculadora de preço de venda para Shopee Brasil: custos, lucro desejado e tarifas.

## Hospedagem

Este projeto é independente e pode ser publicado pelo GitHub Pages em:
https://diiegooh.github.io/precifica-shopee/

Para ativar: Settings > Pages > Build and deployment > Source = Deploy from a branch > Branch = main, Folder = /(root) > Save.

## Tarifas centrais

A página lê `fees.json` na abertura, ao retornar à aba e a cada hora. Mudanças devem ser verificadas na Central do Vendedor e aplicadas neste arquivo após aprovação. O monitoramento via ChatGPT **não altera automaticamente** o GitHub. Tarifas de referência podem variar por conta, CPF/CNPJ, campanhas e regras especiais.

## Produtos e backup

Os produtos são mantidos no armazenamento local do navegador. Use **Exportar backup** e **Importar backup** ao trocar de dispositivo. Exporte CSV para uma planilha. O site não acessa sua conta Shopee nem altera anúncios.
