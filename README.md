# Library App

## Description
The Library App is a software application designed to manage a library's inventory, track borrowed books, and manage user accounts. It provides a user-friendly interface for both librarians and library members.

## Project Structure
- src
  - controllers
    - BookController.ts
    - UserController.ts
  - models
    - Book.ts
    - User.ts
  - services
    - BookService.ts
    - UserService.ts
  - interfaces
    - IBook.ts
    - IUser.ts
  - utils
    - Logger.ts
- tests
  - BookController.test.ts
  - UserController.test.ts
- package.json
- tsconfig.json

## Key Classes and Interfaces
- **BookController**: Manages book-related HTTP requests and responses.
- **UserController**: Manages user-related HTTP requests and responses.
- **BookService**: Contains business logic related to books.
- **UserService**: Contains business logic related to users.
- **Book**: Represents the book entity.
- **User**: Represents the user entity.
- **IBook**: Interface for the book entity.
- **IUser**: Interface for the user entity.
- **Logger**: Utility class for logging messages.

## Usage
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the application using `npm start`.
4. Run tests using `npm test`.

## License
This project is licensed under the MIT License.
