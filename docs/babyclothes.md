# babythings
Teste roupas doc

<h1>teste header</h1>

```mermaid
gantt
    title Baby Clothes Size Roadmap
    todayMarker off
    dateFormat  DD-MM-YYYY
    axisFormat  %d-%m-%Y
    Nascimento : milestone, m1, 23-10-2022, 1d
    section Seasons
    AW           :inv1, 01-10-2022, 185d
    SS           :prim1, after inv1  , 180d
    AW           :after prim1, 180d
    section Sizes
    0-1           :a2, 23-10-2022, 30d
    1-2           :after a2 , 30d
    1-3           :a3, after a2 , 60d
    3-6           :a4, after a3, 60d
    6-9           :a5, after a4, 60d
    9-12           :a6, after a5, 60d
    12-18           :a7, after a6, 180d
    
```

```mermaid
gantt
    title Baby Clothes Size Roadmap pt1
    todayMarker off
    dateFormat  DD-MM-YYYY
    axisFormat  %b%Y
    Nascimento : milestone, m1, 23-10-2022, 1d
    section Seasons
    AW           :inv1, 01-10-2022, 185d
    SS           :prim1, after inv1  , 110d
    section Sizes
    0-1           :a2, 23-10-2022, 30d
    1-2           :after a2 , 30d
    1-3           :a3, after a2 , 60d
    3-6           :a4, after a3, 60d
    6-9           :a5, after a4, 60d
    9-12           :a6, after a5, 60d

    
```

```mermaid
gantt
    title Baby Clothes Size Roadmap pt 2
    todayMarker off
    dateFormat  DD-MM-YYYY
    axisFormat  %b%Y
    section Seasons
    SS           :prim1, after inv1  , 180d
    AW           :after prim1, 180d
    section Sizes

    6-9           :a5, after a4, 60d
    9-12           :a6, after a5, 60d
    12-18           :a7, after a6, 180d
    
```