# what this program is
- This program is a small geometric calculator for search triangle/square/circle area or perimeter
# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square and Triangle.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square and three sides for triangle.
5. Get the answer!

# Math formulas used in program
## Area
- Circle: `S = πR²`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Square: `P = 4a`
- Triangle: `P = a + b + c`

# Example of work with programm
- open programm
```
    Enter figure name, avaliable are ['circle', 'square', 'triangle']:
```
- until we write one of the proposed options, the program will display this message
```
    Enter figure name, avaliable are ['circle', 'square', 'triangle']:
    ITMO
    
    Enter figure name, avaliable are ['circle', 'square', 'triangle']:
    horse
    
    Enter figure name, avaliable are ['circle', 'square', 'triangle']:
    circle 
    
    Enter function name, avaliable are ['perimeter', 'area']:

```
- after that step programm will ask you to enter one of the suggested functions
- and yeah the message was proected until you enter one of the suggested gunction
```
    Enter figure name, avaliable are ['circle', 'square', 'triangle']:
    circle

    Enter function name, avaliable are ['perimeter', 'area']:
    Dr.Livsiy

    Enter function name, avaliable are ['perimeter', 'area']:
    vini puh

    Enter function name, avaliable are ['perimeter', 'area']:
    perimeter
    
    Input figure sizes separated by space, 1 for circle and square, or 3 sides for triangle
```
- the last step it`s input your values for formula
- that step most important, because you can't make mistake, otherwise you need do all again
```
    Enter figure name, avaliable are ['circle', 'square', 'triangle']:
    circle
    
    Enter function name, avaliable are ['perimeter', 'area']:
    perimeter
    
    Input figure sizes separated by space, 1 for circle and square, or 3 sides for triangle
    5

    perimeter of circle is 31.41592653589793
```
- congrats now you know how it works!

## enjoy working with our program