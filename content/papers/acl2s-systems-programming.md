+++
title = "ACL2s Systems Programming"
date = 2022-05-01
[extra]
venue = "ACL2 2022"
authors = ["Andrew T. Walter", "Panagiotis Manolios"]
author-pos = 0
dblp_url = "https://dblp.org/rec/journals/corr/abs-2205-11704.html"
abstract = """
ACL2 provides a systems programming capability that allows one to write code that uses and extends ACL2 inside of ACL2. However, for soundness reasons, ACL2 bars the unrestricted use of certain kinds of programming constructs, like destructive updates, higher-order functions, eval, and arbitrary macros. We devised a methodology for writing code in Common Lisp that allows one to access ACL2, ACL2s, and Common Lisp functionality in a unified way. We arrived at this methodology in the process of developing the ACL2 Sedan (ACL2s) and using it as a key component in formal-methods-enabled projects relating to gamified verification, education, proof checking, interfacing with external theorem provers and security. The methodology includes a library for performing ACL2 queries from Common Lisp, as well as guidelines and utilities that help address common needs. We call this methodology "ACL2s systems programming," to distinguish it from ACL2 systems programming. We show how our methodology makes it possible to easily develop tools that interface with ACL2 and ACL2s, and describe our experience using it in our research.
"""
file = "papers/acl2s-systems-programming.pdf"
+++