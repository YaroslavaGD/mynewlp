Ваша оценка: 310/315
Работа классная, очень понравилось решение с одновременным вводом двух адресов в форме регистрации. Сделано очень аккуратно. Немного валидация просела и редирект
    
    ## Частично выполненные пункты
 - [19/20] Implement client-side validation for the login form, including email and password fields.
 Комментарий: -1 балл можно ввести пробельные символы в начале и в конце email 
![image](https://github.com/YaroslavaGD/virtual-keyboard/assets/37687745/7477c97a-4cc7-4205-aef2-086f664e32d7)

 - [19/20] Display clear error messages indicating any validation issues, such as an improperly formatted email.
Комментарий: -1 балл - ошибка не показывает что нужно ввести именно маленькую букву. Выводится "Пароль должен содержать хотя бы одну букву", даже если введены большие буквы
![image](https://github.com/YaroslavaGD/virtual-keyboard/assets/37687745/59b0dc18-e528-425f-b63d-19eab2f5df4a)

 - [13/15] Redirect users who are already logged in to the main page if they try to access the login page.
 Комментарий: - 2 балла - если залогиненный пользователь вводит напрямую в строке браузера https://fo-sushi.netlify.app/login - то он попадает на логин, нет редиректа на главную страницу
![image](https://github.com/YaroslavaGD/virtual-keyboard/assets/37687745/9c643b56-d363-4aa4-a505-d421be22b93f)

 - [24/25] Implement client-side validation for all required fields in the registration form, such as email, password, first name, last name, date of birth, and address fields (e.g., street, city, postal code, and country) for proper use with CommerceTools.
 Комментарий: -1 балл - можно ввести спец символы для имени и фамили в конце и середине строки
![image](https://github.com/YaroslavaGD/virtual-keyboard/assets/37687745/9d62c283-06ec-4e2a-9aaf-6c70da498b26)

## Выполненные пункты
### Login Integration with Authentication Service
- [x] Integrate the login form with a chosen authentication service (CommerceTools) to handle user authentication.
- [x] Login Implement error handling for failed authentication attempts, such as incorrect email or password, and display user-friendly error messages.
### Redirection
- [x] Redirect users to the application's main page upon successful login.
### Handle Authentication Token
- [x] Obtain the authentication token securely after a successful login attempt by sending a request to the token endpoint (e.g., https://auth.europe-west1.gcp.commercetools.com/oauth/project_key/customers/token), allowing for seamless user authentication across the application.
### Navigation to Registration Page
- [x] Add a button or link on the login page that allows users to navigate to the registration page.
### Registration Input Validation
-  [x] Display clear error messages indicating any validation issues, such as an improperly formatted email or a weak password.
### Registration Integration with Authentication Service
- [x] Integrate the registration form with a chosen authentication service, such as commercetools, to handle user registration.
### State Management, Automatic Login, and Redirection
- [x] Redirect users to the application's main page upon successful account creation and automatic login.
### Integration with commercetools for User Profiles and Addresses
-  [x] Allow users to set a default address during registration.
- [x] Enable users to select different billing and shipping addresses or choose a single address for both billing and shipping during the registration process.
### Navigation to Login Page
- [x] Add a button or link on the registration page that allows users to navigate to the login page.
### Centralized Navigation
- [x] Add links to all the functional pages of the application on the main page. These should include, but are not limited to, the login and registration pages.
-  [x] Each link should redirect the user correctly to the corresponding page without any errors.
### Routing Implementation
- [x] Implement routing for navigation between login, registration, and main pages.
-  [x] Implement a 404 (Not Found) page for invalid route requests.
### Evaluation Criteria for Header
- [x] Navigation to login and registration pages for unauthorized users
-  [x] Ability to access the main page for all users
-  [x] Logout functionality for authorized users
### Penalties for Cross-Check Criteria
- [ ] Absence of Responsive Application Design: If the application does not provide a responsive layout suitable for various devices and screen sizes, a penalty of 20 points will be applied.
- [ ] Errors in the Console: Except for request errors, console errors, including favicon error, will result in a penalty of 20 points. Ensure your code is debugged and free of unnecessary errors for a smooth user experience.
