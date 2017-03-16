##PENDING

#Can Quantum-Mechanical Description of Physical Reality Be Considered Complete ?

Definition: A physical quantity = an observable  
Definition: An observable is an operator satisfying dO(t)/dt = 0 in Heisenberg picture

1. In a complete theory there is an element corresponding to each element of reality.
```coq
Definition complete_theory :
  Isomorphic elements_of_a_complete_theory elements_of_reality
```

2. A sufficient condition for the reality of a physical quantity is the possibility of predicting it with certainty, without disturbing the system.
```coq
Definition k (A:observable) : bool
  predicting A with certainty without disturbing the system
Axiom EPR_criterion_of_reality):
  ⋄k(A) -> A is real
```

3. In quantum mechanics in the case of two physical quantities described by non-commuting operators, the knowledge of one precludes the knowledge of the other.
```
Axiom qm_non_commutativity :
  [A,B] != 0 -> (k(A) -> ~k(B))
```

4. Then either (1) the description of reality given by the wave function in quantum mechanics is not complete or (2) these two quantities cannot have simultaneous reality.
```
(1) -> ((~complete(wavefunction(X))) or (k(A) -> ~k(b)))
```

5. Consideration of the problem of making predictions concerning a system on the basis of measurements made on another system that had previously interacted with it leads to the result that if (1) is false then (2) is also false.
```
~(1) -> (m) [A,B] != 0; ⋄(k(A) and k(B)) // it is possible to have knowledge of either of two physical quantities described by non-commuting operators.
(m) -> (n) (A is real) and (B is real) // both physical quantities correspond to elements of reality
(n) -> ~(2)
∴ ~(1) -> ~(2)
```

6. One is thus led to conclude that the description of reality as given by a wave function is not complete.
```
∴ 1
```


7. Any serious consideration of a physical theory must take into account the distinction between the objective reality, which is of any theory, and the physical independent concepts with which the theory operates.
8. These concepts are intended to correspond with the objective reality, and by means of these concepts we picture this reality to ourselves.
9. In attempting to judge the success of a physical theory, we may ask ourselves two questions: (1) "Is the theory correct?" and (2) "Is the description given by the theory complete?"
10. It is only in the case in which positive answers may be given to both of these questions, that the concepts of the theory may be said to be satisfactory.
11. The correctness of the theory is judged by the degree of agreement between the conclusions of the theory and human experience.
12. This experience, which alone enables us to make inferences about reality, in physics takes the form of experiment and measurement.
13. It is the second question that we wish to consider here, as applied to quantum mechanics.
14. Whatever the meaning assigned to the term *complete*, the following requirement for a complete theory seems to be a necessary one: *every element of the physical reality must have a counterpart in the physical theory*.
15. We shall call this the condition of completeness.
16. The second question is thus easily answered, as soon as we are able to decide what are the elements of the physical reality.
17. The elements of the physical reality cannot be determined by a priori philosophical considerations, but must be found by an appeal to results of experiments and measurements.
18. A comprehensive definition of reality is, however, unnecessary for our purpose.
19. We shall be satisfied with the following criterion, which we regard as reasonable.
20. If, without in any way disturbing a system, we can predict with certainty (i.e. , with probability equal to unity) the value of a physical quantity, then there exists an element of physical reality corresponding to this physical quantity.
21. It seems to us that this criterion, while far from exhausting all possible ways of recognizing a physical reality, at least provides us with one such way, whenever the conditions set down in it occur.
22. Regarded not as a necessary, but merely as a sufficient, condition of reality, this criterion is in agreement with classical as well as quantum-mechanical ideas of reality.
23. To illustrate the ideas involved let us consider the quantum-mechanical description of the behavior of a particle having a single degree of freedom.
24. The fundamental concept of the theory is the concept of state, which is supposed to be completely characterized by the wave function $\psi$, which is a function of the variables chosen to describe the particle's behavior.
25. Corresponding to each physically observable quantity A there is an operator, which may be designated by the same letter.
26. If $\psi$ is an eigenfunction of the operator A, that is, if psiprime \defined Apsi \equiv a psi (1) where a is a number, then the physical quantity A has with certainty the value a whenever the particle is in the state given by P.
27. In accordance with our criterion of reality, for a particle in the state given by P for which Eq. (1) holds, there is an element of physical reality corresponding to the physical quantity A.

##PENDING

Let, for example,
psi = exp(2pi i/h)p_0 x (2)

where h is Planck's constant, po is some constant number, and x the independent variable.
Since the operator corresponding to the momentum of the particle is

p = (h/2pi i) partial_x, (3)

we obtain

psi' = p psi =  (h/2pi i) partial_x psi = po psi (4)

Thus, in the state given by Eq. (2), the momentum has certainly the value pp.
It thus has meaning to say that the momentum of . the particle in the state given by Eq. (2) is real.
On the other hand if Eq. (1) does not hold,
we can no longer speak of the physical quantity
A having a particular value. This is the case, for
example, with the coordinate of the particle. The
operator corresponding to it, say g, is the operator
of multiylication by the independent variable.
Thus,


In accordance with
only say that the
measurement of the
lying between a and

P(a,

b)

=

quantum mechanics we can
relative probability that a
coordinate will give a result
b is

PPdx=

I

dx=b

a. — (6)

Since this probability is independent of a, but
depends only upon the difference b —
a, we see
that all values of the coordinate are equally
probable.
A definite value of the coordinate, for a particle in the state given by Eq. (2), is thus not
predictable, but may be obtained only by a
direct measurement. Such a measurement however disturbs the particle and thus alters its
state. After the coordinate is determined, the
particle will no longer be in the state given by
Eq. (2). The usual conclusion from this in
quantum mechanics is that when the momentnm
of a particle is known, its coordhnate has no physical
reali ty.
More generally, it is shown in quantum mechanics that, if the operators corresponding to
two physical quantities, say A and B, do not
commute, that is, if AB/BA, then the precise
knowledge of one of them precludes such a
of the other. Furthermore,
knowledge
any
attempt to determine the latter experimentally
will alter the state of the system in such a way
as to destroy the knowledge of the first.
From this follows that either (1) t' he guanturnmechanical description of rea1ity given by the wave
function is not cornplele or (2) when the operators
corresponding . to two physical qlantities do not
commute the two quantifies cannot have simultaneous reality. For if both of them had simultaneous reality and thus definite values these
values would enter into the complete description,
according to the condition of completeness. If
then the wave function provided such a complete
description of reality, it would contain these
values; these would then be predictable. This
not being the case, we are left with the alternatives stated.
In quantum mechanics it is usually assumed
that the wave function does contain a complete
description of the physical reality of the system
in the state to which it corresponds. At first

—

—

DES CRI PT ION OF
sight this assumption is entirely reasonable, for
the information obtainable from a wave function
seems to correspond exactly to what can be
measured without altering the state of the
system. We shall show, however, that this assumption, together with the criterion of reality
given above, leads to a contradiction.

PH

YS I CAL REALITY

infinite series (7) is reduced to a single term
)t h(xg)uh(x().
The set of functions u„(x() is determined by
the choice of the physical quantity A. If, instead
of this, we had chosen another quantity, say B,
and eigenhaving the eigenvalues b~, b2, b3,
functions v((x(), v2(x(), v3(x(),
we should
have obtained, instead of Eq. (7), the expansion

2.
For this purpose let us suppose that we have
two systems, I and II, which we permit to interact from the time t =0 to t = T, after which time
we suppose that there is no longer any interaction
between the two parts. We suppose further that
the states of the two systems before t=0 were
known. We can then calculate with the help of
Schrodinger's equation the state of the combined
system I+II at any subsequent time; in particular, for any
T. Let us designate the cor-

t)

responding wave function by +. Ke cannot,
however, calculate the state in which either one
of the two systems is left after the interaction.
This, according to quantum mechanics, can be
done only with the help of further measurements,
by a process known as the reduction of the wave
packet. Let us consider the essentials of this

process.

Let a~, a2, a3,
be the eigenvalues of some
physical quantity A pertaining to system I and
the corresponding
u((x(), u2(x)), us(x(),
eigenfunctions, where x& stands for the variables
used to describe the first system. Then +, considered as a function of x~, can be expressed as
~

+(x(, xm) = Q ))(.(xm)u. (x(),
where x2 stands for the variables used to describe
the second system. Here P„(x&) are to be regarded
merely as the coefficients of the expansion of +
into a series of orthogonal functions u„(x)).
Suppose now that the quantity A is measured
and it is found that it has the value af, . It is then
concluded that after the measurement the first
system is left in the state given by the wave
function uh(x(), and that the second system is
left in the state given by the wave function
ph(x2). This is the process of reduction of the
wave packet; the wave packet given by the

779

4'(x),

xm)

=Q

s=l

((),(x2) v, (x(),

y, 's are the new coeAicients. If now the
quantity 8 is measured and is found to have the
value b„we conclude that after the measurement
the first system is left in the state given by v„(x()
and the second system is left in the state given
where

by

(.(»)

We see therefore that, as a consequence of two
different measurements performed upon the first
system, the second system may be left in states
with two different wave functions. On the other
hand, since at the time of measurement the two
systems no longer interact, no real change can
take place in the second system in consequence
of anything that may be done to the first system.
This is, of course, merely a statement of what is
meant by the absence of an interaction between
the two systems. Thus, it is possible to assign two
different wave functions (in our example )Ih and
e„) to the same reality (the second system after
the interaction with the first).
Now, it may happen that the two wave functions, )th and e„, are eigenfunctions of two noncommuting
operators corresponding
to some
physical quantities P and Q, respectively. That
this may actually be the case can best be shown
by an example. Let us suppose that the two
systems are two particles, and that
+(x& x2)

—

e(2&&ih) (&s—
&2+&o) ndp

—co

where x0 is some constant. Let A be the momentum of the first particle; then, as we have seen
in Eq. (4), its eigenfunctions will be

(x )

e(2m(/h) yes,

(io)

corresponding to the eigenvalue p. Since we have
here the case of a continuous spectrum, Eq. (7)
will now be written

EINSTEIN, PODOLSKY AND ROSEN

780

%(x(, xg)

=

P„(x,)u, (x))dP,
4

where

(x ) —s

This P„however
operator

—(sw(l h) (zg —zo) P

is the eigenfunction

P = (8/2')(7/Bx2,

(12)
of the

(13)

to the eigenvalue —p of the
corresponding
momentum of the second particle. On the other
is the coordinate of the first particle,
hand, if
it has for eigenfunctions

8

to the eigenvalue
corresponding
x, where
delta-function.
well-known
Dirac
the
is
()(xq —
x)
Eq. (8) in this case becomes

where
F2+$0) gldp
e(21r i/h) (x—

= h()(x —xp+xo). (16)
This q, however,
operator

is the eigenfunction

of the

(17)
corresponding to the eigenvalue x+xo of the
coordinate of the second particle. Since

PQ

QP = 1(/2mi,

—

we have shown that it is in general possible for
P~ and p„ to be eigenfunctions of two noncomto physical
muting operators, corresponding

quantities.
Returning now to the general case contemplated in Eqs. (7) and (8),. we assume that P),
and y„are indeed eigenfunctions of some noncommuting operators P and Q, corresponding to
the eigenvalues pI, and q„, respectively. Thus, by
measuring either A or 8 we are in a position to
predict with certainty, and without in any way

disturbing the second system, either the value
of the quantity P (that is p)„) or the ~alue of the
quantity Q (that is q„). In accordance with our
criterion of reality, in the first case we must
consider the quantity I' as being an element of
reality, in the second case the quantity Q is an
element of reality. But, as we have seen, both
wave functions P), and q, belong to the same
reality.
Previously we proved that either (1) the
quantum-mechanical
description of reality given
by the wave function is not complete or (2) when
the operators corresponding
to two physical
quantities do not commute the two quantities
cannot have simultaneous reality. Starting then
that the wave function
with the assumption
does give a complete description of the physical
reality, we arrived at the conclusion that two
operphysical quantities, with rioncommuting
ators, can have simultaneous reality. Thus the
negation of (1) leads to the negation of the only
other alternative (2). We are thus forced to
descripconclude that the quantum-mechanical
tion of physical reality given by wave functions
is not complete.
One could object to this conclusion on the
grounds that our criterion of reality is not sufficiently restrictive. Indeed, one would not arrive
at our conclusion if one insisted that two or more
physical quantities can be regarded as simultaneous elements of reality only +hen they can be
measured or predi cted. On this
simultaneously
point of' view, since either one or the other, but
of the quantities I'
not both simultaneously,
and Q can be predicted, they are not simultaneously real. This makes the reality of P and Q
depend upon the process of measurement carried
out on the first system, which does, not disturb
the second system in any way. No reasonable
definition of reality could be expected to permit
this.
While we have thus shown that the wave
function does not provide a complete description
of the physical reality, we left open the question
of whether or not such a description exists. We
believe, however, that such a theory is possible.


