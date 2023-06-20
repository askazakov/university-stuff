1. Определение кольца
    
    Непустое семейство $\mathscr{D}$ подмножеств из $X$ называют **кольцом**, если
    1. $A,B \in \mathscr{D} \Rightarrow A \cup B \in \mathscr{D}$,
    2. $A,B \in \mathscr{D} \Rightarrow A \setminus B \in \mathscr{D}$


1. Определение алгебры

    Непустое семейство $\mathscr{D}$ подмножеств из $X$ называют **алгеброй**, если
    
    1. $A,B \in \mathscr{D} \Rightarrow A \cup B \in \mathscr{D}$,
    2. $A \in \mathscr{D} \Rightarrow \overline{A}  \in \mathscr{D}$, где $\overline{A} = X \setminus A$
          

1. Определение $\sigma$-алгебры
 
    Алгебру $\mathscr{D}$ называют **$\sigma$-алгеброй**, если из того, что $A_i \in \mathscr{D}$, следует,
    что $\bigcup\limits_{i=1}^{\infty} A_i \in \mathscr{D}$.


1. Определение счётно-аддитивной меры

    Отображение $\mu \colon \mathscr{D} \to [0, +\infty]$ называют **мерой** (счётно-аддитивной или $\sigma$-аддитивной мерой),
если из того, что $A, A_i \in \mathscr{D}$, семейство $\{A_i\}$ счётно или конечно, $A_i$ попарно не пересекаются
и $A = \bigcup\limits_i A_i$, следует, что $\mu{A} = \sum\limits_i \mu{A_i}$.
