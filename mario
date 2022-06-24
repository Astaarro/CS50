#include <cs50.h>
#include <stdio.h>

int get_height(string prompt);

int main(void)
{
    int i = get_height("Height: ");
    switch (i)
    {
       case 1:
            printf("       #\n");
            break;
       case 2:
            printf("       #\n      ##\n");
            break;
       case 3:
            printf("       #\n      ##\n     ###\n");
            break;
       case 4:
            printf("       #\n      ##\n     ###\n    ####\n");
            break;
       case 5:
            printf("       #\n      ##\n     ###\n    ####\n   #####\n");
            break;
       case 6:
            printf("       #\n      ##\n     ###\n    ####\n   #####\n  ######\n");
            break;
       case 7:
            printf("       #\n      ##\n     ###\n    ####\n   #####\n  ######\n #######\n");
            break;
       default:
            printf("       #\n      ##\n     ###\n    ####\n   #####\n  ######\n #######\n########\n");
            break;
    
    }






//    if (i == 1)
//    {
//        printf(".......#\n");
//    }
//   else if (i == 2)
//    {
//        printf(".......#\n......##\n");
//    }
//    else    if (i == 3)
//    {
//        printf(".......#\n......##\n.....###\n");
//    }
//    else    if (i == 4)
//    {
//        printf(".......#\n......##\n.....###\n....####\n");
//    }   
//   else     if (i == 5)
//    {
//        printf(".......#\n......##\n.....###\n....####\n...#####\n");
//    }   
//    else    if (i == 6)
//    {
//        printf(".......#\n......##\n.....###\n....####\n...#####\n..######\n");
//    } 
//     else   if (i == 7)
//    {
//        printf(".......#\n......##\n.....###\n....####\n...#####\n..######\n.#######\n");
//    } 
//    else
//    {
//        printf(".......#\n......##\n.....###\n....####\n...#####\n..######\n.#######\n########\n");
//    }
}

int get_height(string prompt)
{
    int n;
    do
    {
        n = get_int("%s", prompt);
    }
    while (n != 1 && n != 2 && n != 3 && n != 4 && n != 5 && n != 6 && n != 7 && n != 8);
    return n;
     
}
