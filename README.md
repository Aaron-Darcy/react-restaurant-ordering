# React Restaurant Ordering System

A React app for taking orders in a small restaurant. Staff log in to take orders, and administrators can also add and remove menu items.

## Features

- **Login:** separate staff and administrator accounts.
- **Menu:** three sections (hot drinks, food, cold drinks), each on its own screen.
- **Ordering:** choose several items and quantities (for example two coffees and a tea), with a running total.
- **Checkout:** an order number and a printout of the order details.
- **Admin:** add and delete menu items.

## Screenshots

![Login](https://github.com/Aaron-Darcy/WebCompDevProject2023/assets/48316970/fedfb838-cf3d-4344-bf1e-4c55f0422b74)
![Menu](https://github.com/Aaron-Darcy/WebCompDevProject2023/assets/48316970/a842f150-69d8-415d-b64d-f46762209a0d)
![Items](https://github.com/Aaron-Darcy/WebCompDevProject2023/assets/48316970/58253a67-0e02-430d-9f5f-efee2ad7f725)
![Order](https://github.com/Aaron-Darcy/WebCompDevProject2023/assets/48316970/ad7daf19-b7bf-4cf9-bbfd-051378239fc5)
![Checkout](https://github.com/Aaron-Darcy/WebCompDevProject2023/assets/48316970/9112556d-c10e-4a8a-b557-da97fc252a7e)

## Tech stack

React 18 · JavaScript · CSS

## Getting started

```bash
git clone https://github.com/Aaron-Darcy/react-restaurant-ordering.git
cd react-restaurant-ordering
npm install
npm start
```

## Project structure

```
src/
├── components/
│   ├── Authentication/      # login + logout
│   ├── MenuItem/            # HotDrinks, Food, ColdDrinks
│   ├── RestaurantMenu.js
│   ├── MenuOrderManager.js
│   ├── AdminItemForm.js
│   └── Checkout.js
└── data/                    # menu items + demo logins
```

## Context

Web Component Development, CA1, Year 4 Semester 1 (2023). The full brief is in `CA1 Restaurant System.pdf`.
