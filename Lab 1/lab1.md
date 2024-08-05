Lab 1
================
Esteban Samayoa
2024-08-05

# Problema 1

    ## New names:
    ## • `` -> `...10`

``` r
head(TABLA_COMBINADA)
```

    ## # A tibble: 6 × 11
    ##   COD_VIAJE CLIENTE   UBICACION CANTIDAD PILOTO     Q CREDITO UNIDAD Fecha  TIPO
    ##       <dbl> <chr>         <dbl>    <dbl> <chr>  <dbl>   <dbl> <chr>  <chr> <dbl>
    ## 1  10000001 EL PINCH…     76002     1200 Ferna… 300        30 Camio… 01-2…    NA
    ## 2  10000002 TAQUERIA…     76002     1433 Hecto… 358.       90 Camio… 01-2…    NA
    ## 3  10000003 TIENDA L…     76002     1857 Pedro… 464.       60 Camio… 01-2…    NA
    ## 4  10000004 TAQUERIA…     76002      339 Angel…  84.8      30 Panel  01-2…    NA
    ## 5  10000005 CHICHARR…     76001     1644 Juan … 411        30 Camio… 01-2…    NA
    ## 6  10000006 UBIQUO L…     76001     1827 Luis … 457.       30 Camio… 01-2…    NA
    ## # ℹ 1 more variable: ...10 <dbl>

# Problema 2

    ## [1] "LISTA DE NOMBRES"

    ## [[1]]
    ## [1] "Ana"   "Juan"  "Juan"  "Maria" "Pedro"
    ## 
    ## [[2]]
    ## [1] "Carlos" "Carlos" "Luis"   "Miguel" "Ana"   
    ## 
    ## [[3]]
    ## [1] "Sofia" "Sofia" "Sofia" "Juan"  "Pedro"

    ## [1] "MODA DE LA LISTA"

    ## [[1]]
    ## [1] "Juan"
    ## 
    ## [[2]]
    ## [1] "Carlos"
    ## 
    ## [[3]]
    ## [1] "Sofia"

# Problema 3

``` r
head(data)
```

    ## # A tibble: 6 × 11
    ##   ANIO_ALZA MES   NOMBRE_DEPARTAMENTO NOMBRE_MUNICIPIO MODELO_VEHICULO
    ##       <dbl> <chr> <chr>               <chr>            <chr>          
    ## 1      2007 05    HUEHUETENANGO       "HUEHUETENANGO"  2007           
    ## 2      2007 05    EL PROGRESO         "EL JICARO"      2007           
    ## 3      2007 05    SAN MARCOS          "OCOS"           2007           
    ## 4      2007 05    ESCUINTLA           "SAN JOS\xc9"    2006           
    ## 5      2007 05    JUTIAPA             "MOYUTA"         2007           
    ## 6      2007 05    GUATEMALA           "FRAIJANES"      1997           
    ## # ℹ 6 more variables: LINEA_VEHICULO <chr>, TIPO_VEHICULO <chr>,
    ## #   USO_VEHICULO <chr>, MARCA_VEHICULO <chr>, CANTIDAD <dbl>, ...11 <lgl>
