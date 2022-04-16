# Reading Data

<details>
    <summary>Reading from the command line</summary>

scan() function will scan the keyboard until an empty line is specified.

If the file that you are going to read is saved in your working directory, you do not need to specify the whole path to the file or you can use file.choose function.

</details>

<details>
    <summary>Reading from .txt file</summary>

Getting help

```
> ?read.table
```

read.table reads a file and creates a data frame from it. By default it doesn’t have a header.

```
> ourData <- read.table("../Data/data.txt", header = TRUE, sep="")
> head(ourData)
          x         y
1 5.1756426 1.4663523
2 8.3717110 3.8488988
3 0.3805756 1.3589665
4 4.3884145 4.5357171
5 1.9780963 0.5158695
6 0.5544184 0.4695551
```

</details>

<details>
    <summary>Reading from .csv file</summary>

Getting help

```
> ?read.csv
```

csv stands for comma-separated values. read.csv reads a file and creates a data frame from it. By default it has a header and the values are separated sep by ,.

```
> pokemon <- read.csv("../Data/pokemon.csv")
> head(pokemon)
  Number       Name Type_1 Type_2 Total HP Attack Defense Sp_Atk Sp_Def Speed
1      1  Bulbasaur  Grass Poison   318 45     49      49     65     65    45
2      2    Ivysaur  Grass Poison   405 60     62      63     80     80    60
3      3   Venusaur  Grass Poison   525 80     82      83    100    100    80
4      4 Charmander   Fire          309 39     52      43     60     50    65
5      5 Charmeleon   Fire          405 58     64      58     80     65    80
6      6  Charizard   Fire Flying   534 78     84      78    109     85   100
  Generation isLegendary Color hasGender Pr_Male Egg_Group_1 Egg_Group_2
1          1       False Green      True   0.875     Monster       Grass
2          1       False Green      True   0.875     Monster       Grass
3          1       False Green      True   0.875     Monster       Grass
4          1       False   Red      True   0.875     Monster      Dragon
5          1       False   Red      True   0.875     Monster      Dragon
6          1       False   Red      True   0.875     Monster      Dragon
  hasMegaEvolution Height_m Weight_kg Catch_Rate     Body_Style
1            False     0.71       6.9         45      quadruped
2            False     0.99      13.0         45      quadruped
3             True     2.01     100.0         45      quadruped
4            False     0.61       8.5         45 bipedal_tailed
5            False     1.09      19.0         45 bipedal_tailed
6             True     1.70      90.5         45 bipedal_tailed
```

```
> titanic <- read.csv("../Data/titanic.csv")
> head(titanic)
  PassengerId Survived Pclass
1           1        0      3
2           2        1      1
3           3        1      3
4           4        1      1
5           5        0      3
6           6        0      3
                                                 Name    Sex Age SibSp Parch
1                             Braund, Mr. Owen Harris   male  22     1     0
2 Cumings, Mrs. John Bradley (Florence Briggs Thayer) female  38     1     0
3                              Heikkinen, Miss. Laina female  26     0     0
4        Futrelle, Mrs. Jacques Heath (Lily May Peel) female  35     1     0
5                            Allen, Mr. William Henry   male  35     0     0
6                                    Moran, Mr. James   male  NA     0     0
            Ticket    Fare Cabin Embarked
1        A/5 21171  7.2500              S
2         PC 17599 71.2833   C85        C
3 STON/O2. 3101282  7.9250              S
4           113803 53.1000  C123        S
5           373450  8.0500              S
6           330877  8.4583              Q
```
