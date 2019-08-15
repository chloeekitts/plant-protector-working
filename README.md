![alt](assets/img/Plant-Protector-LOGO.svg)

# Plant-Protector
Mobile App to ease the workload while gardening. Accomplished by using ESP8266 controllers and Web data to inform user to take action in the garden.

This App tracks the growing cycle of your peppers, and provides information on methods to produce the best harvest.

## Installation
### For Mobile
```bash
Clone Repository
```

```bash
npm install
```
```bash
expo start
```
### For Web
```bash
Clone Repository
```
```bash
npm install
```
```bash
expo start --web


## Github Repository/Development Files

* https://github.com/thegroupthatworkz/Plant-Protector.git


## Tools Used

- React with Material Design UI
- Javascript
- HTML
- CSS
- Expo CLI
- ESP8266 controllers
- NodeJS
- Firebase


### Wireframs and Planning

![alt](assets/img/wireframe1.png)

![alt](assets/img/wireframe2.png)

![alt](assets/img/wireframe3.png)


## UX/UI Design

Home Page

![alt](assets/img/home.png)

Product Page

![alt](assets/img/product.png)

Information Page

![alt](assets/img/info.png)

Weather Section

![alt](assets/img/weather.png)


## Initial Design ****USE GIF***** - NEED THESE DESIGNS (MAKE IN AI) 

UX/UI Iterations 

![alt](assets/img/mockups.gif)


## Final Design ****USE GIF***** - NEED THESE SCREEN SHOTS OF FINAL

![alt](assets/img/mockups-final.gif)


## API Server Routes

```
router.get("/orders",                  function(req, res) {...})
router.post("/order/create",           function(req, res) {...})
router.get("/orders/:user_id",         function(req, res) {...})
router.get("/orderproducts/:order_id", function(req, res) {...})

router.get("/products",                function(req, res) {...})
router.get("/products/:id",            function(req, res) {...})
router.post("/products/add",           function(req, res) {...})

router.get("/tables/drop",             function(req, res) {...})
router.get("/tables/load",             function(req, res) {...})
```

## Challenges

