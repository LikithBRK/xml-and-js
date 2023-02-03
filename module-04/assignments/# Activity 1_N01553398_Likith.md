# Activity 1

Generate folowing XPath queries for `module-4/products.xml` file

1. Target 2nd product in the list
    
    //product[2]
    ![image info](../assignments/act1_1.png)

2. Target last product in the list
    
    (//product[last()])
    ![image info](../assignments/act1_2.png)

3. Target `sku` attribute of the first product

    //product[1]//@sku
    ![image info](../assignments/act1_3.png)

4. Target all products with manufacturer id `sjb-pet`

    //product/manufacturer[@id='sjb-pet']
    ![image info](../assignments/act1_4.png)
