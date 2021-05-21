## Qualification task for frontend developers

### Objective

Develop a UI for display users table data with
an **infinite scroll** and **possibility to sort users by columns**

### Technical requirements

1. Code quality should be a production level. Those, quality level which you will write every day in our project.
2. Project should be created with [create-react-app](https://reactjs.org/docs/create-a-new-react-app.html).
3. It is desirable (not required) that project should be written with [TypeScript](https://www.typescriptlang.org) language.
4. To display table you should use [Ant Design](https://ant.design) UI library.
5. Do not waste your time on custom styles and animations. Just use default **Ant Design** styles.
6. Use **usersApiService** class as backend mock. Class located in **users-api.service.ts** file in this repository.
7. Table data should dynamically load with **infinite scroll** interaction behavior.
   First page index for users data on a backend is **1**.
8. Users can be optionally sorted by each table columns in ascending or descending order.
   There are should be a possibility to sort users by several columns at once.
9. You should handle case when backend responded with error and show error message to user
   with [ant design notification](https://ant.design/components/notification)
10. Please save your code in separate github repository and send a link to us.
