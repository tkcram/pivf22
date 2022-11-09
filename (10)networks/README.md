# Homework Week 10 - Hierarchy

## The Concept
For this week's homework, the goal was to recreate an existing tree cluster diagram. The original, found [here](https://www.harmony.org.uk/book/examples/fg_1p1p3.gif), is a specifc type of cluster tree diagram used in linguistic called a [phrase-structure diagram](https://en.wikipedia.org/wiki/Phrase_structure_rules). These diagrams are used to demonstrate that sentences are ordered and structured in meaningful ways, and were some of the earliest attempts at a universal grammar.

## The Data
The data data for this week is a custom JSON blob with each entry containing 1-2 fields. All entries contain the 'id' of the node, and all non-leaf entries contain a list of children. The data was created based on the structure given in the sample image.

## The Viz
Given that the goal was to replicate the original diagram, the chart has minimal flair. Some changes were made from the original however, including inverting the bolding for better clarity, and using lines in place of arrows as the downward flow is implicitic.

The code to create the viz is reasonably standard, follwing the link/edge structure provided in the class code. One addition was to provide both text labels as well as node shapes. The text by itself became difficult to read with the lines going through it, and creating a background in CSS proved challenging. The solution was to keep the shapes on the node (albeit changing them to squares) and give them a white fill.

## Links

The source code is available [here](https://github.com/tkcram/pivf22/tree/main/(10)networks) and the output image is available below

![The viz pre-interaction](https://raw.githubusercontent.com/tkcram/pivf22/main/(10)networks/sentence.png) 
