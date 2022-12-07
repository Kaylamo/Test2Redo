# Test2Redo
A.

integers = [0-9]+  all postive ints
 <identifier> --> <letter> {<character>}

    <variables>--> a | b ... | z | A ... | Z

    <char>--> <letter> | <digit> | _

    <int_literal>--> 0 | 1 | 2 | ... | 9

    <num>--> <digit> {<digit>}

    <operations> --> + | -  | *  | /  
                   | ( | )  | % | ;
                   | < | <= | >  | >= | = | /=

int =  7 * num + 5;
int = identifier
=	equal_sign
7	int_literal
*	mul_op
num	identifier
+	add_op
5	int_literal
;	semicolon


B.

<prgm> --> category Main() {<stmt_list>}
<expr> -> <term>{+ | -} <term>}
<term> -> <factor>{(* | / | %) <factor>}
<factor> ->  id | int_literal | '('<expr>')'
<var> -> "k" | "l" | "m"
constant -> digit{digit}
digit -> "0" | "1" | "..." | "9"

num = int | dot = float | word = String | say = print |
small = short | big = long | twice = double
| so = if | otherwise = else
well = for | dew = do | whilst = while

C. Top Down Parser
-uses BNf/EBNF
-reads from the left-right
E -> E + T | E - T | T
T -> T * F | T / F | T % F |F
F ->  id | int_literal | (E)
V -> "k" | "l" | "m"
C -> D{D}
D -> "0" | "1" | "..." | "9"

D. I used unambiguos grammar

E. code
F. Syntax Code
G.
![image1](https://user-images.githubusercontent.com/66099207/206093764-c6d40aa7-7c89-4a25-8f5a-cd9759e513da.png)

![image3](https://user-images.githubusercontent.com/66099207/206093815-d2f1c864-daea-49e1-8bbb-15287d1f9461.png)

![image2](https://user-images.githubusercontent.com/66099207/206093834-909ae6e9-478b-4da2-ac14-237eb64e8ce1.png)




