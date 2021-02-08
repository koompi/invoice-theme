# KOOMPI OFFICIAL INVOICE TEMPLATE

This template is for using internally with SmallWorld on Manager.io platform.

## INSTALLATION

To use this template you need to follow the instruction below.

- Login to manager.io
- Settings > Themes > New Theme > Add thene name
- Copy everything in [official-invoice.liquid](./official-invoice.liquid])
- Paste in Theme > Create

## SETTING UP

There some extra setups need to be done in order to comply with the theme requirements for it fields:

### Custom Fields

- **Business Details**
  - New Custom Field > bank_name > Show custom field on printed documents > Create
  - New Custom Field > bank_no > Show custom field on printed documents > Create
  - New Custom Field > city_en > Show custom field on printed documents > Create
  - New Custom Field > city_kh > Show custom field on printed documents > Create
  - New Custom Field > company_name_en > Show custom field on printed documents > Create
  - New Custom Field > company_name_kh > Show custom field on printed documents > Create
  - New Custom Field > khan_en > Show custom field on printed documents > Create
  - New Custom Field > khan_kh > Show custom field on printed documents > Create
  - New Custom Field > no_en > Show custom field on printed documents > Create
  - New Custom Field > no_kh > Show custom field on printed documents > Create
  - New Custom Field > sangkat_en > Show custom field on printed documents > Create
  - New Custom Field > sangkat_kh > Show custom field on printed documents > Create
  - New Custom Field > str_en > Show custom field on printed documents > Create
  - New Custom Field > str_kh > Show custom field on printed documents > Create
  - New Custom Field > telephone > Show custom field on printed documents > Create
  - New Custom Field > vattin > Show custom field on printed documents > Create

- **Customer**
  - New Custom Field > attn > Show custom field on printed documents > Create
  - New Custom Field > company_kh > Show custom field on printed documents > Create
  - New Custom Field > company_en > Show custom field on printed documents > Create
  - New Custom Field > telephone > Show custom field on printed documents > Create

- **Sales Invoice**
  - New Custom Field > exchange_rate > Show custom field on printed documents > Create
  - **New Custom Field > invoice_type > Type Drop-down list > Options for drop-down list >**
    - **tax_invoice**
    - **commercial_invoice**
    **> Show custom field on printed documents > Create**

### Forms Default

- Sale Invoice
  - Custom Theme > The new theme name you just create
  - invoice_type > tax_invoice

### Business Logo

Upload your company letter head image

### Business Details

Fill all of your company information
