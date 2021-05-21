# Constant-variable
int i=10;
int j=20;
int const *ptr = &i;
now can we do this => ptr = &j;
YESSSSSSSSSSSSSSSSSS! 
why because , ptr is pointing towards an constant integer, its not itself constant, it says that i am pointing towards a constant integer and i'll not change that, but i can change myself.s 
#if we want to make a constant pointer
we need to write;
int * const ptr = &i;
