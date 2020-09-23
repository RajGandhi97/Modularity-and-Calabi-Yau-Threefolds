# Modularity-and-Calabi-Yau-Threefolds
In a book by Christian Meyer titled "Modularity of Calabi-Yau Threefolds", the author counted points on various Calabi-Yau threefolds over finite fields, and compared these point counts to coefficients appearing in the L-series of certain newforms with the goal of finding numerical evidence for the modularity of the threefolds in question. In the current project, we study quotients of many "non-rigid" Calabi-Yau threefolds in Meyer's book by various automorphism groups, with hopes that the quotient is modular and "rigid" (this technique originally appeared in a paper by Dominik Burek). It is an open problem whether the L-series of every weight 4 newform equals the L-series of a rigid Calabi-Yau threefold. 

All code was written in the Magma programming language. 

This project was co-supervised by Colin Ingalls and Adam Logan and supported by an Undergraduate Student Research Award from the Natural Sciences and Engineering Research Council. I would like to thank my supervisors for suggesting the methods used in this project and for their help with debugging. I would also like to John Voight for allowing me to use his server to run the Magma script. 

We have found numerical evidence for two new rigid realizations of weight 4 newforms that do not seem to be in the literature:

-The Calabi-Yau X_8 on page 112 of Meyer's book appears to be rigid with newform 54/2. 

-The Calabi-Yau (A:B:C:D:E:F)=(0:2:1:1:1:2) on page 91 of Meyer's book appears to be rigid with newform 168/2. 

