# Numerals

Zerita is using two parallel number systems, a decimal and a hexadecimal one. The decimal
is only present to help with the passages coming from languages, but the hexadecimal one
is the one that should be used otherwise.

Numbers are in hexadecimal unless a subscript is present.

Both numbering systems use big billions for the naming.

## Hexadecimal numbers and writing

Zerita is using 0-9 and A-F for writing the numbers, and there is no chance of misunderstanding
as words use only lowercase letters to be written. The preferred grouping for numbers is with
an underscore, as it's unambiguous.

The numbers that have a basic name are:

| Hexadecimal | Decimal            | Name  |
| ----------- | ------------------ | ----- |
| 0           | 0<sub>10</sub>     | nula  |
| 1           | 1<sub>10</sub>     | uno   |
| 2           | 2<sub>10</sub>     | dos   |
| 3           | 3<sub>10</sub>     | tres  |
| 4           | 4<sub>10</sub>     | tetra |
| 5           | 5<sub>10</sub>     | pente |
| 6           | 6<sub>10</sub>     | ses   |
| 7           | 7<sub>10</sub>     | septe |
| 8           | 8<sub>10</sub>     | okto  |
| 9           | 9<sub>10</sub>     | nove  |
| A           | 10<sub>10</sub>    | deka  |
| B           | 11<sub>10</sub>    | lona  |
| C           | 12<sub>10</sub>    | bili  |
| D           | 13<sub>10</sub>    | san   |
| E           | 14<sub>10</sub>    | dort  |
| F           | 15<sub>10</sub>    | piec  |
| 10          | 16<sub>10</sub>    | anim  |
| 100         | 256<sub>10</sub>   | cem   |
| 1_000       | 4_096<sub>10</sub> | alf   |

### Larger numbers

The number system after 999_999 (16_777_215<sub>10</sub>) is using powers of 1_000_000
(16_777_216<sub>10</sub>) to create names for arbitrary large numbers.

| Hexadecimal       | Decimal                          | Name               |
| ----------------- | -------------------------------- | ------------------ |
| 1_000_000         | 16_777_216<sub>10</sub>          | bet                |
| 1_000_000_000_000 | 281_474_976_710_656<sub>10</sub> | bet ad dos potente |

## Decimal numbers and writing

The preferred grouping for numbers is with still with an underscore, as it's unambiguous.

There are two decimal numbers that need a special name, which are 100<sub>10</sub> (64 in hexadecimal),
called is "sent", and 1_000<sub>10</sub>, called "mil".

### Larger numbers

The number system after 999_999<sub>10</sub> (3E7) is using powers of 1_000_000<sub>10</sub> (3E8)
to create names for arbitrary large numbers.

| Decimal                        | Hexadecimal   | Name                  |
| ------------------------------ | ------------- | --------------------- |
| 1_000_000<sub>10</sub>         | F4_240        | milonu                |
| 1_000_000_000_000<sub>10</sub> | E_8D4_A51_000 | milonu ad dos potente |

## Examples

| Hexadecimal   | Decimal                     | Name                                                                          | Decimal Name                                                                                |
| ------------- | --------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| B             | 11<sub>10</sub>             | lona                                                                          | deka uno                                                                                    |
| 11            | 17<sub>10</sub>             | anim uno                                                                      | deka ses                                                                                    |
| 5B            | 91<sub>10</sub>             | penteanim lona                                                                | novedeka uno                                                                                |
| 33D           | 829<sub>10</sub>            | trescem tresanim san                                                          | oktosent dosdeka nove                                                                       |
| 973           | 2_419<sub>10</sub>          | novecem sesanim tres                                                          | dos mil tetrasent deka nove                                                                 |
| 7_D04         | 32_004<sub>10</sub>         | septe alf sancem tetra                                                        | tresdeka dos mil tetra                                                                      |
| AA_AAA        | 699_050<sub>10</sub>        | dekanim deka alf dekacem dekanim deka                                         | sessent novedeka nove mil pentedeka                                                         |
| 1_234_567_89A | 78_187_493_530<sub>10</sub> | alf doscem tresanim tetra bet pentacem sesanim sept alf oktocem noveanim deka | septedeka okto mil sent oktodeka sept milonu tetrasent novedeka tres mil pentesent tresdeka |
