From Yi Chen

To use this code, first make sure fastjet and root are both setupped
(including fastjet-contrib)
then compile and run as follows
./RunExample HiForest.root Output.root
The soft-dropped result is stored in Output.root
The messenger.* stuff is just to set branch addresses and get entries etc, they don't really matter in terms of soft drop

This code will give you basic soft drop quantities
If you need to do further studies, for example the response with different stopping depths and things with the CA tree, I have other custom soft drop code that allows more flexibility


