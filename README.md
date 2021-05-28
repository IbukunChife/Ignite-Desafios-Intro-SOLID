  ### TurnUserAdminUseCase
  [x] should be able to turn an user as admin
  [x] should not be able to turn a non existing user as admin
 
  ### User model
  [x] should be able to create an user with all props
 
  ### UsersRepository
  [x] should be able to create new users 
  [x] should be able to list all users 
  [x] should be able to find user by ID 
  [x] should be able to find user by e-mail address
  [x] should be able to turn an user as admin
 
  ### ListAllUsersUseCase
  [x] should be able to list all users
  [x] should not be able to a non admin user get list of all users
  [x] should not be able to a non existing user get list of all users

  ### ShowUserProfileUseCase
  [x] should be able to get user profile by ID
  [x] should not be able to show profile of a non existing user


  ### CreateUserUseCase
  [x] should be able to create new users
  [x] should not be able to create new users when email is already taken

  
  ### Testes das Rotas
  
[POST] /users
  [x] should be able to create new users
  [x] should not be able to create new users when email is already taken
[PATCH] /users/:user_id/admin
  [x] should be able to turn an user as admin
  [x] should not be able to turn a non existing user as admin
[GET] /users/:user_id
  [x] should be able to get user profile by ID
  [x] should not be able to show profile of a non existing user
[GET] /users
  [x] should be able to list all users
  [x] should not be able to a non admin user get list of all users
  [x] should not be able to a non admin user get list of all users
  [x] should not be able to a non existing user get list of all users