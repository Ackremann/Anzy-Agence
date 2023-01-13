# Anzy Agence

ERP Car Management by flutter❤️ 

![anzy showcase](https://user-images.githubusercontent.com/59745489/212119852-49917f70-0423-4ea0-a927-a7960e06d28b.png)

## ⚙ Tools Used
- Flutter 
- Dart
- Drift (sqlite)
- Fluent UI for windows
- Bloc

## ✨ Features
✔ Beautiful UI.\
✔ User Authentication "SignUp, SignIn" with Permission system\
✔ Light & Dark mode.\
✔ The design is suitable for all screen sizes.\
✔ CRUD Car, User, Importer, Customer, Reports and advance Search.\



# Screenshots
  Splash Page                 |   Login Page        |  Home Page
:-------------------------:|:-------------------------:|:-------------------------:
![Screenshot (2)](https://user-images.githubusercontent.com/59745489/212123787-8ff8351a-5b33-44c0-b95a-fe8215d24219.png)|![Screenshot (3)](https://user-images.githubusercontent.com/59745489/212123794-bb94466f-20c9-4d51-8cfb-a3ec6cd55922.png)|![Screenshot (4)](https://user-images.githubusercontent.com/59745489/212123803-cd978b85-e9d1-4aaf-bf17-92f81dab1158.png)

  Car Brands Page                |   Car Models Page      |  Importer Page
:-------------------------:|:-------------------------:|:-------------------------:
![Screenshot (5)](https://user-images.githubusercontent.com/59745489/212123809-ab1efe1d-f413-4c4d-b3bb-bcb513d141e3.png)|![Screenshot (6)](https://user-images.githubusercontent.com/59745489/212123811-744e6b5b-0c02-487d-9509-925e531f4b2e.png)|![Screenshot (7)](https://user-images.githubusercontent.com/59745489/212123814-ee3e3de4-c7aa-4948-9ff8-8e3b3523bd1f.png)

  Report Page (sold)                 |   Importer Car Page        |  Avilable Car Page
:-------------------------:|:-------------------------:|:-------------------------:
![Screenshot (8)](https://user-images.githubusercontent.com/59745489/212123815-92b6a290-396d-4c44-8273-5321ceb632f7.png)|![Screenshot (10)](https://user-images.githubusercontent.com/59745489/212123816-8c234540-8024-49e0-963f-a8b591791aed.png)|![Screenshot (11)](https://user-images.githubusercontent.com/59745489/212123818-a1d921ce-1ff7-445b-814c-0d52684497ec.png)

  Contract Page             | Car Detail Page    
:-------------------------:|:-------------------------:
![Screenshot (12)](https://user-images.githubusercontent.com/59745489/212126236-06e98335-ef83-4fe4-b5b7-9b9a6cc2baae.png)|![Screenshot (13)](https://user-images.githubusercontent.com/59745489/212126243-6e3cd90d-7110-467a-82e4-350410513e4b.png)

## Directory Structure

```
lib
│
│──── core
│     │─── database
│     │    └── daos
│     │    │   │── brand_dao.dart
│     │    │   │── car_dao.dart
│     │    │   |── contract_dao.dart
│     │    │   │── customer_dao.dart
│     │    │   │── importer_dao.dart
│     │    │   |── expenses_dao.dart
│     │    │   │── model_dao.dart
│     │    │   │── owner_dao.dart
│     │    │   │── user_dao.dart
│     │    │   └── contract_dao.dart
│     │    └── tables
│     │    │   │── brand_table.dart
│     │    │   │── car_table.dart
│     │    │   |── contract_table.dart
│     │    │   │── customer_table.dart
│     │    │   │── importer_table.dart
│     │    │   |── expenses_table.dart
│     │    │   │── model_table.dart
│     │    │   │── owner_table.dart
│     │    │   │── user_table.dart
│     │    │   └── contract_table.dart
│     │    └── drift_database.dart
│     │─── utils
│     │     │── media_query_values.dart
│     │     └── strings_manager.dart
│     │─── validator
│     │     └── validator.dart
│     │─── widgets
│     │     │── infobar.dart
│     │     │── show_dialog.dart
│     │     └── text_field.dart
|     │
│──── features
│     │─── report
│     │     │── cubit
│     │     │   │── report_cubit.dart
│     │     │   └── report_state.dart
│     │     │── units
│     │     │   │─── report_table.dart
│     │     │   │─── report_bottom.dart
│     │     │   └── report_header.dart
│     │     └── main_report_view.dart
│     │─── auth ...
│     │─── car ...
│     │─── code_car ...
│     │─── contract ...
│     │─── home ...
│     │─── login ...
│     │─── splash ...
│     │ 
│──── config
│     └─── magic_router.dart
│──── app.dart.dart
│──── bloc_observer.dart
│──── injection_container.dart
└──── main.dart    
```


## Packages

![carbon (1)](https://user-images.githubusercontent.com/59745489/212337665-a07845e0-fd26-430f-aefa-c02d7cd4c33d.png)

