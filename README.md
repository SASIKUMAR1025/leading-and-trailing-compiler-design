# leading-and-trailing-compiler-design
Lead :- Lead is a list of all those terminals symbols("operators") which can appear first on any right hand side of a production.
For each non-terminal i.e. left hand side,a Lead list containing the first terminal in each production for that non-terminal.Where a non-terminal is the first symbol on the right hand side, include both it and the first terminal following.e.g. for
X →→ a.... / Bc
includes a,c and B in X's Lead List.
Trail:- Trail or Last is a similar list of those terminals which can appear Last.
For each non-terminal i.e. left hand side,a Last or trail list containing the last terminal in each production for that non terminal.Where a non-terminal is the last symbol on the right hand side, include both it and the last terminal .e.g. for
Y →→ ....u / ....vW
includes u,v and W in Last or Trail list.
