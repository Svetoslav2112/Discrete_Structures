## Задача 06.

Да се докаже, че за произволни множества <img src="https://latex.codecogs.com/svg.latex?\Large&space;A,B,C"> е изпълнено:<br><img src="https://latex.codecogs.com/svg.latex?\Large&space;A\times{(B\setminus{C})}=(A\times{B})\setminus{(A\times{C})}">.

*Док-во:*

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\subseteq)"> Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\times{(B\setminus{C})}}">. Следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;\exists{a\in{A}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\in{(B\setminus{C})}">, т.ч. <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=(a,b)">. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\in{B}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\notin{C}\Rightarrow{x=(a,b)}\in{A\times{B}}">.<br>Да сопуснем, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\times{C}}">. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;\exists{a'}\in{A}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;c\in{C}">, т.ч. <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=(a',c)">. Но <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=(a,b)"> и следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=(a,b)=(a',c)\Rightarrow{a=a'}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;b=c">, но <img src="https://latex.codecogs.com/svg.latex?\Large&space;c\in{C}">, от където <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\in{C}">, което е противоречие с допускането, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\times{C}}\Rightarrow{x\notin{A\times{C}}}">. Така <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{(A\times{B})\setminus{(A\times{C})}}">.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\supseteq)"> Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in(A\times{B})\setminus{(A\times{C})}">. Следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\times{B}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{A\times{C}}">. От <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\times{B}}"> следва, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;\exists{a\in{A}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\in{B}">, т.ч. <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{(a,b)}">.<br>Да допуснем че <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\in{C}">. Тогава понеже <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{A}"> имаме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=(a,b)\in{A\times{C}}">, което е противоречие.<br>Следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\notin{C}"> и т.к. <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\in{B}">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\in{B\setminus{C}}">. Така <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=(a,b)\in{A}\times{(B\setminus{C})}">.