Lab3 Esteban Samayoa
================
Esteban Samayoa
2024-08-28

# Problema 1

    ##   total_movies
    ## 1       388269

    ##   total_directors
    ## 1           86880

# Problema 2

    ## # A tibble: 1 × 1
    ##   average_genres
    ##            <dbl>
    ## 1           2.41

# Problema 3

    ## # A tibble: 1,174,675 × 3
    ##    role                             number_of_movies number_of_people
    ##    <chr>                                       <int>            <int>
    ##  1 ""                                         164782           304819
    ##  2 " (1985)"                                       1                1
    ##  3 " (1991 reissue only)"                          1                1
    ##  4 " (episode \"Protest und Theori"                1                3
    ##  5 " (episode 4: The Criminal)"                    1                1
    ##  6 " (episode Målbrott)"                           1                3
    ##  7 " (episode one)"                                1                4
    ##  8 " (episode two)"                                1                2
    ##  9 " (segment \"A Boca\")"                         1                2
    ## 10 " (segment \"A Suspeita\")"                     1                1
    ## # ℹ 1,174,665 more rows

# Problema 4

    ## # A tibble: 117,393 × 6
    ## # Groups:   director_id, first_name [85,794]
    ##    director_id first_name      last_name number_of_movies number_of_actors genre
    ##          <int> <chr>           <chr>                <int>            <int> <chr>
    ##  1           1 Todd            1                        1               NA <NA> 
    ##  2           2 Les             12 Poiss…                1               NA Short
    ##  3           3 Lejaren         a'Hiller                 2               NA Drama
    ##  4           4 Nian            A                        1               NA <NA> 
    ##  5           5 Khairiya        A-Mansour                1               NA Docu…
    ##  6           6 Ricardo         A. Solla                 1               NA Drama
    ##  7           6 Ricardo         A. Solla                 1               NA Short
    ##  8           8 Kodanda Rami R… A.                      35               NA Acti…
    ##  9           9 Nageswara Rao   A.                       1               NA <NA> 
    ## 10          10 Yuri            A.                       1               NA Come…
    ## # ℹ 117,383 more rows

# Problema 5

    ## # A tibble: 300,617 × 4
    ## # Groups:   movie_id, first_name [299,547]
    ##    movie_id first_name   last_name number_of_roles
    ##       <int> <chr>        <chr>               <int>
    ##  1        0 Jeff         Jingle                  2
    ##  2        2 Richard (I)  Brooks                 20
    ##  3        5 Charles R.   Seeling                 1
    ##  4        6 Vincent      McEveety               32
    ##  5        7 George       Lessey                 12
    ##  6        7 Harry (I)    Grossman               12
    ##  7        9 Frank (I)    Lloyd                   4
    ##  8       11 James P. (I) Hogan                  50
    ##  9       15 Gregory (I)  Cooke                   3
    ## 10       16 Ernest C.    Warde                  10
    ## # ℹ 300,607 more rows
