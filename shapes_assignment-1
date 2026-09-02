#include <graphics.h>
#include <conio.h>
int main()
{
    int gd = DETECT, gm;


    initgraph(&gd, &gm, (char*)"");

    //Straight Line
    line(50, 50, 250, 50);
    outtextxy(50, 30, (char*)"Line");

    //Circle
    circle(400, 150, 60);
    outtextxy(360, 70, (char*)"Circle");

    //Rectangle
    rectangle(50, 200, 250, 350);
    outtextxy(50, 180, (char*)"Rectangle");

    //Triangle
    int tri[] = {
        400, 350,
        480, 220,
        560, 350,
        400, 350
    };

    drawpoly(4, tri);
    outtextxy(440, 200, (char*)"Triangle");

    
    getch();

    return 0;
}
