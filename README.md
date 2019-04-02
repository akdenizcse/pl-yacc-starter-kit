# pl-yacc-starter-kit

This is a logic language which allows only conjunction and printing the result.

\<program\> : \<stmts\>

\<stmts\> : \<stmt\>
	| \<stmt\> ; \<stmts\>

\<stmt\> : print \<expr\>;
	| \<assign\>;

\<assign\> : \<lhs\> = \<rhs\>;

\<lhs\> : \<var\>

\<rhs\> : \<var\>
	| \<expr\>
	| \<expr\> and \<expr\>


