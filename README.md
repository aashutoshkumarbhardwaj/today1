                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            //given co-ordinate x y of centre of circle and its radius write a program that will determine whether a point lies inside a circle or outside or on the circle


#include<stdio.h>
#include<math.h>
int main()
{
    int x1,x2,x3,y1,y2,y3,dis,dis2;
    printf("enter the cordinaterof center ");
    scanf("%d%d",&x1,&y1);
    printf("ennter the cordiate of radii");
    scanf("%d%d",&x2,&y2);
    printf("eter the cordinate of point");
    scanf("%d%d",&x3,&y3);
    dis=sqrt(pow(2,x2-x1)+pow(2,y2-y1));
    dis2=sqrt(pow(2,x3-x1)+pow(2,y3-y1));
    if (dis>dis2)
    {
       printf("the point is inside the circle\n");
    }
    else if(dis=dis2)
    printf("the point is on tje cercumference\n");
    else
    printf("the point is outside the circle\n");
     
   return 0;




}
