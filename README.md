# DEX670 Production Ready Integration Best Practice

## Org info
- ORGID : 07b33dd1-ea6b-4a01-8713-8ebdcfde9c9f
- ORG_CLIENT_ID : 4d8cc95850d1432880cc4c901084933d
- ORG_CLIENT_SECRET : c9cE2c9cC89b40eab1ebE121cC856787

## Connected apps
- Exchange Viewer
  - 45d298d6076645899d932ab4f84d5d42
  - 6468BC2719404114B7930b36141bfDeA
- Exchange Contributor
  - 6a945aa5dcae4625a9eb8f84a45c8db3
  - FBf09b7177A442189B2B33B9b702075B




l2k28ss.sid3fjfd5_Zsrq9cK9hNsqrSTfu8ji334EEVW83hjskShnodE


curl -i -X POST -H "Content-Type: application/json" -H "Authorization: Bearer l2k28ss.sid3fjfd5_Zsrq9cK9hNsqrSTfu8ji334EEVW83hjskShnodE" -d "{ \"intent\":\"sale\", \"payer\": {\"payment_method\":\"paypal\" }, \"transactions\":[ { \"amount\":{\"total\":\"80.00\", \"currency\":\"USD\" }, \"description\": \"Check-In Baggage.\", \"custom\": \"ANYAIRLINE_90048630024435\",\"invoice_number\": \"48787589673\", \"payment_options\":{\"allowed_payment_method\":\"INSTANT_FUNDING_SOURCE\" },\"soft_descriptor\":\"ANYAIRLINE BAGGAGE\" } ], \"note_to_payer\":\"Behappy.\" }" https://training-paypal-fake-api-sandbox-mjf1rw.5sc6y6-1.usa-e2.cloudhub.io/v1/payments/payment