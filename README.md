# Frontend Development Project

## The subject 

A developer make the api of the shop stock management application and they lost the frontend you have to make the frontend of the application. The application is a simple stock management application where you can add, delete, update and view the products. The application should have the following features:

1. Add a product
2. Delete a product
3. Update a product
4. View all products
5. View a single product
6. Search for a product by name price or quantity (optional)
7. Sort the products by name price or quantity (optional)
8. Filter the products by price or quantity (optional)

#### The project is in **React** with **TypeScript** and **Vite**.

You are free for the choice of the rest of the stack.
**BUT** you have to follow the rules and best practices mentioned below, and use only secure and standard packages.

--- 

**You have a starting point with the project**

#### **BUT** you can improve it as you want. And go as far as you want.

---

## How start working on the project

1. Fork the repository
2. Clone the repository
3. Install the dependencies
4. Start the development server
5. Start working on the project
6. Push your changes to your forked repository
7. Create a pull request to the original repository to a branch with your name
8. Wait for the review of your code
9. If everything is ok, your code will be merged to the original repository
10. If not, you will receive feedback and you have to fix the issues
11. Repeat the steps 6 to 10 until your code is merged
12. You can ask for help if you need
13. You can ask for more features if you want

## The rules

### TypeScript Rules
1. Strict mode is mandatory - enable all strict flags in tsconfig
2. No usage of `any` type - always define proper types
3. No type assertions unless absolutely necessary (avoid `as`)
4. Use interface for object types instead of type aliases when possible
5. Enable and follow strict null checks
6. Define explicit return types for functions
7. Use discriminated unions for complex state handling
8. No implicit returns in complex functions
9. Prefer readonly arrays and properties when data shouldn't be modified
10. Use enum only for simple, constant values - prefer union types for complex cases

### React Component Rules
1. Use functional components exclusively
2. Props interface must be defined for all components
3. Children prop must be explicitly typed
4. Event handlers must have proper TypeScript event types
5. Use controlled components for forms
6. Implement proper loading and error states
7. Extract reusable logic into custom hooks
8. Keep components focused and small (under 100 lines)
9. Use proper React.memo() optimization only when necessary
10. Implement proper cleanup in useEffect hooks

### Code Quality Rules
1. Enforce consistent code formatting
2. Use meaningful variable and function names
3. Keep functions pure when possible