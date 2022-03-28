# Sequelize Computer Store
Rest API CRUD and settings sequelize using `Node Js & Postman`


## Project Computer Store
<ul>
  <li>Settings sequelize for SQL database</li>
  <li>CRUD Admin.</li>
  <li>CRUD Customer.</li>
  <li>CRUD Product.</li>
  <li>AUTH (Authentication dan Authorization) with <strong> md5 jsonwebtoken.</strong> </li>
  <li>Transaction.</li>
</ul>

## Command Sequelize
### Table `product`
sequelize model:create --name product --attributes name:string,price:double,stock:double,image:string

### Table `admin`
sequelize model:create --name admin --attributes name:string,username:string,password:string

### Table `customer` 
sequelize model:create --name customer --attributes name:string,phone:string,address:string,image:string,username:string,password:string

### Table `transaksi`
sequelize model:create --name transaksi --attributes customer_id:integer,waktu:date

### Table `detail_transaksi`
equelize model:create --name detail_transaksi --attributes transaksi_id:integer,product_id:integer,price:double,qty:double


## Result of Relation in Database

![image](https://user-images.githubusercontent.com/87308406/156081931-56acf1c6-d29b-4f9d-98a2-928c3ebeb162.png)
