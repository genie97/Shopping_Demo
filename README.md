# Shopping Mall Demo

- Service Flow

  1) Sign Up

  2) Sign In

  3) Product Cart

  4) Product Payment

  

- Domain

  1) User

  | ID           | INT              |
  | ------------ | ---------------- |
  | **NAME**     | **VARCHAR(50)**  |
  | **PASSWORD** | **VARCHAR(50)**  |
  | **ADDRESS**  | **VARCHAR(100)** |
  | **PHONE**    | **VARCHAR(13)**  |

  2) Product

  | ID        | INT             |
  | --------- | --------------- |
  | **NAME**  | **VARCHAR(50)** |
  | **TYPE**  | **VARCHAR(50)** |
  | **PRICE** | **INT**         |
  | **STOCK** | **INT**         |
  | **IMG**   | **VARCHAR(50)** |

  3) Cart

  | ID             | INT             |
  | -------------- | --------------- |
  | **USER_ID**    | **INT**         |
  | **PRODUCT_ID** | **INT**         |
  | **QUANTITY**   | **INT**         |
  | **VALIDITY**   | **BOOLEAN**     |
  | **ADDRESS**    | **VARCHAR(50)** |

  
