<h1 align="center">E-Commerce Data Analysis</h1>
<p align="center"  style="font-size: 25px">🛒🛒🛒🛒🛒</p>

## 🧰 Tools
- Python
- SQL
- Pandas
- Numpy
- Matplotlib
- Seaborn
- HTML
- CSS

## 🗂️ Documentation
1. Pre-processing
    - Transforming
        ```
        def conv_tgl(column):
            return column.dropna().map(parser.parse)

        item = ['Order_Date', 'Delivery_Date']
        data[item] = data[item].apply(conv_tgl)
        data.info()
        ```
        
    - Cleansing
        ```
        data_new = data.dropna()
        data_new.info()
        ```

    
2. Processing (Result)
    
    - Average Price of Products Sold        
        ![Gambar](https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/screenshot.png)
        
                
    - Highest Total Sales Products          
        ![Gambar](https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/screenshot2.png)

    - Product Category that Has the Highest Price          
        <b>Highest Price</b>        
        ![Gambar](https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/screenshot3_p.png)        
        <b>Highest Price/pcs</b>        
        ![Gambar](https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/screenshot3_p_.png)        
        <b>Highest Quantity</b>        
        ![Gambar](https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/screenshot3_q.png)             

    - Sales Growth
        <img src='https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/g_1.png' alt="Gambar" width="100%"/>

    - Sales Patterns in a Week        
        <img src='https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/g_3.png' alt="Gambar"/>

    - Statistical Analysis of Objects in Data
        ![Gambar](https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/screenshot4.png)

    - Correlation of Payment Methods and Total Shopping
        <img src='https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/g_4.png' alt="Gambar" width="100%"/>

    - Percentage of Order Delivery Delays
        <img src='https://raw.githubusercontent.com/artatara7a/e_commerce-data-analysis/master/docs/g_5.png' alt="Gambar" width="100%"/>