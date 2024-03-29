# This is a demo made with Vue and ant-design-vue of sales data visualisation dashboard.

![Screenshot](About/Screenshot.png)

## How to run:

1. Clone the repository:

```
git clone https://github.com/Leo-Ma0502/Admin_Dashboard_Vue.git
```

2. Start the backend:

```
cd admin_dashboard_vue
cd backend
npm install
npm run start
```

3. Start the front end:

```
cd vue-demo or cd ../vue-demo
npm install
npm run dev
```

4. open http://127.0.0.1:5173/ in browser

### Users should be in default directed to the welcome page saying "welcome to demo page".

When they try to navigate to profile or chart pages, they will be redirected to login page, where they may login with either of these:

```
[
{
"id": 0,
"username": "user0",
"password": "pwd0"
},
{
"id": 1,
"username": "user1",
"password": "pwd1"
},
{
"id": 2,
"username": "user2",
"password": "pwd2"
}
]
```

### Users may also choose to create a new use and then login.

### After logging in

users could see their login status in the profile page, or logout by simply clicking the logout in menu, they may browse the data chart from menu bar to see charts, where they could add something to the chart by clicking on "update".
