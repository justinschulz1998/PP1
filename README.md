# PP1

## Goal
All of the PPn practical exercises have the same goal: for you to prove step-by-step that you could follow the lessons given in the weekly lectures. By proving week after week, that you understood what was going on, I as the lecturer get valuable feedback over your personal status. 

In this first exercise, you'll have to prove, that you understood the concept of digital calculation by mapping an element of an input-set to an element of an output set. We will start simple and increase the difficulty throughout the exercise. While working on this and start a stop-watch and work continuously for 90 minutes straight. After 90 minutes - you stop! Write down at which stage you had to stop.

## Workflow
The workflow for each of these exercises will be pretty much the same. 
1) Fork
2) Modify and Commit
3) Post your link for Review

### Fork
A fork is a user-local copy of this repository. You can change it as you please, you can delete it and start over, it's your local working copy of this project.
The best thing is, unless you delete it on purpose, it'll stay within your local user-space and you can always go back and revisite it. 

To fork this repository into your own user-space, please first create a user-account on the github-platform. You may use your universities email address, or any other.

![Fork-Button](./assets/fork.png)


Then open the link to this project in your browser and press the `Fork` button in the upper right hand corner as shown in the picture above.

A dialog opens, scroll down and click the `Create fork` button, as shown below.

![Create fork-Button](./assets/create_fork.png)

### Modify and Commit
"to commit" means to save changes into your repository. 
Now that you have a local copy of the project, you can modify it. For this exercise, everything you need to do can be done from within the browser. 

Click onto the filename `README.md`. It'll forward you to a larger view of the document. In the upper right hand corner, you'll find a pencil button:

![Pencil-Button](./assets/pencil.png)
![Commit-Button](./assets/commit_button.png)

After selecting `edit in place` you can use the integrated text-editor to modify this document. When you are done, or you want to save in between, just click the `commit changes` button in the top right-hand corner. THis will open a dialog and give you the opportunity to attach a comment to your commit. Please comment with problems you had until there and how much time it took you to get to that commit.

### Encountering Problems
It's not uncommon to encounter problems while trying to solve these puzzles. If you have any questions, use each PPs discussion forum, which can always be found under the address: `<repository-link>/discussions`. So in this case: https://github.com/MaxClerkwell/PP1/discussions.

### Post your Link for Review
Use the button "Add solution" in moodle, to hand in the link to your repository!

## Tasks

### Mapping Symbols to Binary
Fill out the following table, mapping the numbers '0'-'15' to [binary combinations](https://github.com/STEMgraph/8fd3f76a-24d1-460b-9f88-9ff63809e8f5). 

| Decimal    | Binary Represenations |
|------------|-----------------------|
| 0          |     0000            |
| ....          |                   |
| 15        |          ???          |

How many digits do you need? Explain how you could [calculate the amount](https://github.com/STEMgraph/556cc1c6-a1f0-4008-8a6c-20707bfdd1e8):
<details>
    <summary>Your Answer</summary>
    Erase this text and write your answer here!
</details>

### Mapping Binary to Binary

The trick with [processors](https://github.com/STEMgraph/bd1f3943-c439-497a-a6a9-513c6ed7ce80) is that they feature [digital gates](https://github.com/STEMgraph/2ba87074-5f0a-4949-a25c-a34ab7fcce1e) that implement [logical functions](https://github.com/STEMgraph/9a437897-663d-442b-82bd-f34643db7e4e). 
These logical functions can electronically map from an input-set of voltages to an output-set of voltages. 

Look at this truthtable:

| Carry-In (C<sub>in</sub>) | B | A | Sum (S) | Carry-Out (C<sub>out</sub>) |
|---------------------------|---|---|---------|-----------------------------|
| 0                         | 0 | 0 | 0       | 0                           |
| 0                         | 0 | 1 | 1       | 0                           |
| 0                         | 1 | 0 | 1       | 0                           |
| 0                         | 1 | 1 | 0       | 1                           |
| 1                         | 0 | 0 | 1       | 0                           |
| 1                         | 0 | 1 | 0       | 1                           |
| 1                         | 1 | 0 | 0       | 1                           |
| 1                         | 1 | 1 | 1       | 1                           |

This table can be implemented by only using NAND gates as the following animation shows. By clicking on the digital inputs on the lefthand side, you can simulate different states (click on the picture to get to the animation).
<a href="https://circuitverse.org/users/305021/projects/full-adder-nand-990621f6-993b-4676-a1b5-2a31aae451ce">
  ![Full Adder NAND](https://maxclerkwell.github.io/svg_storage/digital-circuits/full_adder_nand/transparent_background.svg)
</a>

---

Create a truth-table for a 2-bit adder, without a Carry-In bit. What's the set of possible input objects? What's the set of possible output objects? 

>   Your
>
>   table
>
>   goes
>
>   here!

### Finding the Boolean Equations
Use the [K-Map method](https://github.com/STEMgraph/4b957490-badf-4264-b9f2-1b5aa370f36e) to write down the boolean equations for each of the output-bits.
Fill out the following K-Maps:

Write down the defining equation for each output-cell, that contains a `1`. And combine them with an `OR` gate. Try to minimize the equations as good as possible.

<details>
    <summary>The final functions</summary>
    
    Q<sub>0</sub> = .......
    
    Q<sub>1</sub> = .......
    
    C<sub>out</sub> = .......

</details>

### Implement your circuit
Based on the boolean equations you just produced, implement a logic network in CircuitVerse showing the functionality of at least one bit!

<details>
    <summary>Your solution</summary>
    A share link to your solution goes here: <a href=".................">Link!</a>
</details>