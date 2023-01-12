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
│     │─── app_prefs
│     │    └── app_prefs.dart
│     │─── assets
│     │    └── images
│     │         └── app_images.dart
│     │─── constant
│     │     │── failure_messages.dart
│     │     │── strings.dart
│     │     └── success_messages.dart
│     │─── enum
│     │     │── product_type_enum.dart
│     │     └── text_form_typ_enum.dart
│     │─── error
│     │     │── exceptions.dart
│     │     └── failures.dart
│     │─── language
│     │     └── language_manager.dart
│     │─── models
│     │     │── auth_model.dart
│     │     │── favorite_model.dart
│     │     │── product_model.dart  
│     │     └── user_data.dart
│     │─── navigator
│     │     └── navigator.dart
│     │─── network
│     │     │── apis.dart
│     │     │── dio_helper.dart
│     │     │── end_points.dart
│     │     └── network_info.dart
│     │─── routes
│     │     │── router.dart
│     │     └── routes.dart
│     │─── theme
│     │     │── bloc
│     │     │   └── cubit
│     │     │       │── theme_cubit.dart
│     │     │       └── theme_state.dart
│     │     │── colors.dart
│     │     └── themes.dart
│     └─── validators
│           │── validate_messages.dart
│           └── validators.dart
│
│──── features
│     │─── cart
│     │     │── data
│     │     │   │─── datasources
│     │     │   │   └── cart_remote_datasources.dart
│     │     │   │─── model
│     │     │   │   │── add_cart_model.dart
│     │     │   │   │── cart_model.dart
│     │     │   │   └── update_cart.dart
│     │     │   └─── repositories
│     │     │       └── cart_repo_impl.dart
│     │     │── domain
│     │     │   │─── repositories
│     │     │   │   └── cart_repo.dart
│     │     │   │─── usecases
│     │     │   │   └── cart_usecase.dart
│     │     └── presentation
│     │         │─── bloc
│     │         │   └── cubit
│     │         │       │── cart_cubit.dart
│     │         │       └── cart_state.dart
│     │         │─── pages
│     │         │   └── cart_page.dart
│     │         └─── widgets
│     │             └── cart_item.dart
│     │
│     │─── categories ...
│     │─── check_out ...
│     │─── favorite ...
│     │─── filter ...
│     │─── home ...
│     │─── login ...
│     │─── orders ...
│     │─── payment_methods ...
│     │─── product ...
│     │─── profile ...
│     │─── shipping_addresses ...
│     │─── sign_up ...
│     └─── splash ...
│
│──── widgets
│     │─── animated_button_widget.dart
│     │─── button_widget.dart
│     │─── cached_network_image_widget.dart
│     │─── circle_button.dart
│     │─── favorite_button_widget.dart
│     │─── flutter_toast_widget.dart
│     │─── list_tile_item_widget.dart
│     │─── loader_widget.dart
│     │─── offline_widget.dart
│     │─── product_item.dart
│     │─── products_grid_view.dart
│     │─── products_list_view.dart
│     │─── rating_bar_builder.dart
│     │─── rating_bar_count_widget.dart
│     │─── rating_bar_count_widget.dart
│     └─── text_form_field_widget.dart
│
│──── injection_container.dart
└──── main.dart    
```


## Packages

![image](https://user-images.githubusercontent.com/60518534/210802806-582352c1-5f94-4a35-bc09-57aba5c7cea1.png)
## Feedback

If you have any feedback, please reach out to us at mahmoud3laa2210@gmail.com

## 🔗 You can follow me on

[![portfolio](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MahmoudAlaa22)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoudalaa2210/)
