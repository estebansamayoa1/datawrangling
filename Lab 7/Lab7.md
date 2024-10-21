Lab 7
================
Esteban Samayoa
2024-10-21

### Columnas Health Data

    ## [1] "rating"            "title"             "text"             
    ## [4] "product_id"        "parent_id"         "user_id"          
    ## [7] "timestamp"         "verified_purchase"

### Columnas Health MetaData

    ## [1] "main_category"  "title"          "average_rating" "rating_number" 
    ## [5] "price"          "store"          "details"        "parent_id"

### Cuántos productos contienen reviews con las palabras “love”, “recommend” y “enjoy”?

    ## [1] 117

### De los reviews de la pregunta 1, encuentre el top 5 de las tiendas que los venden?

    ##                 store n
    ## 1                     7
    ## 2              ASUTRA 5
    ## 3           DownBeats 3
    ## 4            Bestrice 2
    ## 5                JUNP 2
    ## 6              Jitner 2
    ## 7 Sweetsation Therapy 2
    ## 8             Syntrax 2
    ## 9           sequel 65 2

### Genere un wordcloud sin stopwords de los reviews de la pregunta 1.

![](Lab7_files/figure-gfm/unnamed-chunk-7-1.png)<!-- -->

### Generar un wordcloud de los reviews de las 5 tiendas encontradas en la pregunta 2. Deberá de incluir todos los reviews de esas 5 tiendas.

![](Lab7_files/figure-gfm/unnamed-chunk-8-1.png)<!-- -->

### Cuáles son las 25 palabras más frecuentes de los reviews?

    ##      love      like recommend   product     enjoy       one    really      just 
    ##       115       100        95        82        81        76        75        72 
    ##       can      well       use      will      also       get     great      good 
    ##        70        66        65        60        57        54        54        51 
    ##     using      time    highly    little     first      much     water      skin 
    ##        49        48        41        40        39        38        36        35 
    ##      foam 
    ##        34
