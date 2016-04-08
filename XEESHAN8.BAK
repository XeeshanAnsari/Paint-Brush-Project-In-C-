#include<conio.h>
#include<graphics.h>
#include<stdlib.h>
#include<stdio.h>
#include<dos.h>
void helpf()
{
void *img1;
unsigned size;
size=imagesize(1,1,640,480);
img1=(void *) malloc(size);
getimage(1,1,640,480,img1);
setcolor(0);
setfillstyle(1,0);
bar(0,0,640,480);
setfillstyle(1,7);
bar(80,90,460,310);
setcolor(0);
settextstyle(1,0,1);
bar(250,40,305,60);
outtextxy(245,40," INSTRUCTION ");
setcolor(0);
settextstyle(0,0,1);
outtextxy(90,100,"1 Press Alt+z to select the Rectangle.");
settextstyle(2,0,0);
outtextxy(100,110," * Press ctrl+arrow key to draw the Rectangle.");
line(80,125,450,125);
settextstyle(0,0,1);
outtextxy(90,130,"2 Press Alt+x to select the Eraser.");
settextstyle(2,0,0);
outtextxy(100,140," * Press up/down arrow to maximize and minimize the Eraser.");
outtextxy(100,150," * Press ctrl+arrow key to use the Eraser.");
line(80,165,450,165);
settextstyle(0,0,1);
outtextxy(90,170,"3 Press Alt+c to select the circle.");
settextstyle(2,0,0);
outtextxy(100,180," * Press ctrl+up/down arrow key to draw a cicrle.");
line(80,195,450,195);
settextstyle(0,0,1);
outtextxy(90,200,"4 Press Alt+v to select C.Rectangle.");
settextstyle(2,0,0);
outtextxy(100,210," * Press ctrl+arrow key to draw C.Rectangle.");
line(80,225,400,225);
settextstyle(0,0,1);
outtextxy(90,230,"5 Press Alt+b to write the text");
line(80,240,400,240);
settextstyle(0,0,1);
outtextxy(90,250,"6 Press F1 to change the color.");
settextstyle(0,0,1);
outtextxy(90,270,"7 Press F2 for floodfill.");
line(80,260,460,260);
line(100,90,100,300);
line(80,280,460,280);
outtextxy(90,290,"8 Press Alt+n to open options MENU.");
line(80,300,460,300);
setfillstyle(1,8);
bar(75,85,460,95);
bar(460,85,470,310);
bar(80,300,470,310);
bar(85,90,75,310);
setfillstyle(0,0);
settextstyle(7,0,1);
setcolor(15);
outtextxy(150,380,"Press any key to continue");
getche();
putimage(0,0,img1,COPY_PUT);
}
void title()
{
int i;
setfillstyle(1,2);
bar(1,1,640,480);
//******************************FOR SQUARE BORDER**************
for(i=10; i<640; i++)
{
setfillstyle(1,15);
bar(0,0,10+i,10);
delay(1);
bar(640,470,640-i,480);
delay(1);
bar(630,0,640,10+i);
delay(1);
bar(0,480,10,470-i);
delay(1);
}
//******************************FOR DASHING BORDER*****************
for(i=10; i<680; i++)
{
setcolor(15);
setfillstyle(1,0);
bar(640,473,640-i+1,476);
bar(0,5,12+i-1,8);
bar(633,1,636,1+i);
bar(5,480,8,464-i-1);
delay(1);
}
//************************* for brush *******************
setfillstyle(1,17);
bar(450,230,570,250);
setcolor(0);
rectangle(450,230,570,249);
setfillstyle(1,14);
bar(490,150,530,229);
setcolor(0);
rectangle(490,150,530,229);
for(i=0; i<120; i++)
{
i=i+1;
setcolor(15);
line(450+i,250,450+i,300);
}
//*************************************FOR TITLE**********************
settextstyle(12,0,4);
setcolor(15);
outtextxy(70,20,"IN THE NAME OF ALLAH THE MOST BENEFICANT & THE MOST MERCIFUL");
setcolor(0);
line(70,29,540,29);
for(i=1; i<60; i++)
{
settextstyle(1,0,3);
setcolor(1);
outtextxy(25+i,40,"ALIGARH INSTITUTE OF TECHNOLOGY");
setcolor(2);
outtextxy(25+i,40,"ALIGARH INSTITUTE OF TECHNOLOGY");
delay(1);
}
settextstyle(1,0,3);
setcolor(1);
outtextxy(25+i,40,"ALIGARH INSTITUTE OF TECHNOLOGY");
settextstyle(12,0,4);
setcolor(15);
outtextxy(180,80,"8th ENGINEERING & IT FAIR 2014-2015");
setfillstyle(10,1);
bar(68,199,470,200);
bar(68,203,470,204);
setcolor(15);
settextstyle(4,0,4);
outtextxy(90,160,"PAINT BOX PROJECT");
for(i=1; i<125; i++)
{
setcolor(0);
settextstyle(1,0,1);
outtextxy(50,425-i,"GROUP MEMBERS");
setcolor(2);
outtextxy(50,425-i,"GROUP MEMBERS");
}
setcolor(0);
settextstyle(1,0,1);
outtextxy(50,425-i,"GROUP MEMBERS");
for(i=1; i<120; i++)
{
setcolor(8);
settextstyle(12,0,15);
outtextxy(25+i,330,"1 Zeeshan Ansari");
setcolor(2);
outtextxy(25+i,330,"1 Zeeshan Ansari");
}
setcolor(8);
settextstyle(12,0,15);
outtextxy(65,330,"1 Zeeshan Ansari");
for(i=1; i<120; i++)
{
setcolor(8);
settextstyle(12,0,1);
outtextxy(25+i,340,"2 Muhammad Firas");
setcolor(2);
outtextxy(25+i,340,"2 Muhammad Firas");
}
setcolor(8);
settextstyle(12,0,1);
outtextxy(65,340,"2 Muhammad Firas");
for(i=1; i<120; i++)
{
setcolor(8);
settextstyle(12,0,1);
outtextxy(25+i,350,"3 Abdul Wahab ");
setcolor(2);
outtextxy(25+i,350,"3 Abdul Wahab ");
}
setcolor(8);
settextstyle(12,0,1);
outtextxy(65,350,"3 Abdul Wahab ");
for(i=1; i<120; i++)
{
setcolor(8);
settextstyle(12,0,1);
outtextxy(25+i,360,"4 Syed Zain Haider");
setcolor(2);
outtextxy(25+i,360,"4 Syed Zain Haider");
}
setcolor(8);
settextstyle(12,0,1);
outtextxy(65,360,"4 Syed Zain Haider");
for(i=1; i<120; i++)
{
setcolor(8);
settextstyle(12,0,1);
outtextxy(25+i,370,"5 Abdullah");
setcolor(2);
outtextxy(25+i,370,"5 Abdullah");
}
setcolor(8);
settextstyle(12,0,1);
outtextxy(65,370,"5 Abdullah");
for(i=1; i<50; i++)
{
setcolor(0);
settextstyle(12,0,2);
outtextxy(500-i,350,"GROUP ADVISOR");
setcolor(2);
outtextxy(500-i,350,"GROUP ADVISOR");
}
setcolor(0);
settextstyle(12,0,2);
outtextxy(500-i,350,"GROUP ADVISOR");
setcolor(15);
settextstyle(1,0,2);
outtextxy(450,360,"SIR MASOOD");
//**************** PRESS ENTER TO OPEN PAINT*********************
setcolor(0);
settextstyle(1,0,2);
outtextxy(140,430,"PRESS ANY KEY TO OPEN PAINT BOX");
setfillstyle(1,24);
bar(130,430,515,431);
bar(130,430,131,460);
setfillstyle(1,7);
bar(513,430,515,462);
bar(130,461,515,462);
getch();
setfillstyle(1,0);
bar(0,0,640,480);
}
//********************** fOr paint bRush design On background ***********
void design()
{
int i,j;
setfillstyle(1,7);
bar(0,0,640,480);
setfillstyle(1,15);
bar(60,40,640,412);
setcolor(1);
setfillstyle(1,1);
bar(0,0,640,19);
setcolor(1);
setfillstyle(1,1);
bar(0,460,640,480);
setcolor(15);
settextstyle(0,0,1);
outtextxy(588,8,"-");
setcolor(15);
rectangle(609,7,615,13);
setcolor(15);
settextstyle(0,0,1);
outtextxy(20,8," Untited-paint ");
setcolor(0);
settextstyle(0,0,0);
outtextxy(5,25,"File Edit View Image Color Help ");
setcolor(15);
rectangle(585,4,600,16);
setcolor(15);
rectangle(605,4,620,16);
setfillstyle(1,4);
bar(625,4,640,16);
setcolor(15);
rectangle(625,4,640,16);
settextstyle(0,0,1);
outtextxy(630,8,"X");
setcolor(0);
ellipse(15,221,1,360,7,5);
rectangle(8,200,23,208);
line(10,175,20,185);
line(32,208,45,208);
line(40,203,45,203);
line(35,196,32,208);
line(42,196,40,203);
line(35,196,42,196);
line(45,203,45,208);
circle(40,100,5);
line(43,105,48,110);
line(45,103,50,108);
setcolor(0);
settextstyle(1,0,2);
outtextxy(37,140,"A");
setfillstyle(1,24);
bar(4,416,5,440);
bar(4,416,33,417);
setfillstyle(1,15);
bar(33,416,33,440);
bar(33,440,4,440);
setcolor(0);
rectangle(15,426,26,436);
setcolor(15);
rectangle(9,420,20,431);
setfillstyle(1,0);
bar(9,420,19,430);
setcolor(0);
ellipse(40,177,270,90,4,4);
setcolor(0);
ellipse(40,186,90,270,4,4);
setcolor(24);
line(0,40,60,40);
line(0,412,60,412);
for(i=0; i<120; i+=13)
{
j=i+15;
setcolor(i);
setfillstyle(1,i);
bar(37+i,420,47+i,430);
setcolor(24);
rectangle(37+i,420,47+i,430);
setcolor(j);
setfillstyle(1,j);
bar(37+i,432,47+i,442);
setcolor(24);
rectangle(37+i,432,47+i,442);
}
setcolor(0);
line(0,445,640,445);
setfillstyle(1,24);
bar(60,40,640,42);
setfillstyle(1,24);
bar(60,410,640,412);
setfillstyle(1,24);
bar(60,40,62,412);
setcolor(0);
settextstyle(0,0,0);
outtextxy(2,450,"For Help, click Help Topics on the Help Menu. ");
setcolor(2);
setfillstyle(1,2);
bar(0,460,65,480);
setcolor(15);
settextstyle(0,0,1);
outtextxy(20,465,"Start ");
setfillstyle(1,24);
bar(10,245,45,246);
setfillstyle(1,24);
bar(10,245,11,295);
setfillstyle(1,15);
bar(45,245,45,295);
bar(10,295,45,295);
setcolor(0);
line(35,217,45,217);
line(35,225,45,225);
ellipse(45,221,270,90,2,4);
ellipse(35,221,90,270,2,4);
line(18,120,12,132);
line(22,122,16,134);
ellipse(20,121,1,360,2,1);
line(12,132,12,136);
line(16,134,12,136);
line(12,132,16,134);
line(17,102,12,107);
line(20,105,16,109);
line(16,100,22,106);
line(23,96,26,99);
line(23,96,16,100);
line(22,106,26,99);
line(12,107,12,111);
line(16,109,12,111);
line(12,107,16,109);
setfillstyle(1,14);
bar3d(10,82,18,85,8,18);
rectangle(35,50,50,58);
line(15,45,12,50);
line(15,45,18,50);
line(18,50,23,53);
line(23,53,20,56);
line(12,50,8,53);
line(8,53,11,56);
line(11,56,12,61);
line(12,61,16,58);
line(16,58,23,61);
line(23,61,20,56);
line(45,75,52,82);
line(50,80,45,85);
line(49,79,44,84);
line(47,87,40,80);
line(40,80,45,75);
line(52,82,47,87);
for(i=0; i<5; i++)
{
setcolor(i);
ellipse(40,82,50,200,2+i,4+i);
ellipse(13,158,50,200,2+i,4+i);
}
setcolor(0);
line(19,152,24,157);
line(24,157,20,161);
line(20,161,15,156);
line(15,156,19,152);
line(19,152,13,151);
line(15,156,13,151);
setfillstyle(1,17);
bar(36,127,46,128);
setfillstyle(1,14);
bar(39,126,43,120);
setcolor(0);
rectangle(39,126,43,120);
for(i=0; i<12; i++)
{
i=i+1;
setcolor(15);
line(35+i,129,35+i,135);
}
}
/////////****************** for fcircle*************//////
void fcircle(int x,int y)
{
char key1, key2;
int r=1,a=0;
setcolor(7);
outtextxy(500,435,"circle ........");
setcolor(0);
outtextxy(500,435,"Fill circle ........");
line(13,274,42,274);
line(13,274,13,288);
setcolor(15);
line(42,275,42,288);
line(13,288,42,288);

while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
if (key2==59) a++;
if (key2==80 ) r++;
if (key2==72 ) r--;
setcolor(a);
circle(x,y,r);
}
}
setcolor(7);
outtextxy(500,435,"Fill circle ........");
line(13,274,42,274);
line(13,274,13,288);
line(42,275,42,288);
line(13,288,42,288);
setcolor(0);
outtextxy(500,435,"circle ........");
}
/////////****************** for scircle*************//////
void scircle(int x,int y)
{
char key1, key2;
int r=1,a=0;
setcolor(7);
outtextxy(500,435,"circle ........");
setcolor(0);
outtextxy(500,435,"Simple circle ........");
line(13,250,42,250);
line(13,250,13,265);
setcolor(15);
line(42,250,42,265);
line(13,265,42,265);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
setcolor(15);
circle(x,y,r);
if (key2==59) a++;
if (key2==80 ) r++;
if (key2==72 ) r--;
setcolor(a);
circle(x,y,r);
}
}
setcolor(7);
outtextxy(500,435,"Simple circle ........");
line(13,250,42,250);
line(13,250,13,265);
line(42,250,42,265);
line(13,265,42,265);
setcolor(0);
outtextxy(500,435,"circle ........");
}

//****************************** for circle fUntion ****************
void mycircle(int x,int y)
{
char key1, key2;
setcolor(0);
outtextxy(500,435,"circle ........");
ellipse(28,258,1,360,12,3);
ellipse(28,280,1,360,12,3);
setfillstyle(1,0);
floodfill(28,280,0);
line(5,213,26,213);
line(5,213,5,230);
setcolor(15);
line(15,270,40,270);
line(26,213,26,230);
line(5,230,26,230);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
putpixel(x,y,15);
if (key2==72 && y>44) y--;
if (key2==80 && y<408) y++;
if (key2==75 && x>64) x--;
if (key2==77 && x<640) x++;
putpixel(x,y,0);
if (key2==59) scircle(x,y);
if (key2==60) fcircle(x,y);
}
}
setcolor(7);
outtextxy(500,435,"circle ........");
ellipse(28,258,1,360,12,3);
ellipse(28,280,1,360,12,3);
setfillstyle(1,7);
floodfill(28,280,7);
line(15,270,40,270);
line(5,213,26,213);
line(5,213,5,230);
line(26,213,26,230);
line(5,230,26,230);
}
 ///**************for fill rectangle funtion*************////
void frectangle(int x1,int y1, int x2, int y2 )
{
char key1, key2;
int a=0;
setcolor(7);
outtextxy(500,435,"Rectangle ......");
setcolor(0);
outtextxy(500,435,"Fill Rectangle ......");
line(13,275,42,275);
line(13,275,13,290);
setcolor(15);
line(42,275,42,290);
line(13,290,42,290);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
if (key2==59) a++;
if (key2==72 && x2>x1 && y2>y1) x2-- && y2--;
if (key2==80 && x1>64 && x2<640 && y1>44 && y2<408) x2++ && y2++;
setcolor(a);
rectangle(x1,y1,x2,y2);
}
}
setcolor(7);
outtextxy(500,435,"Fill Rectangle ......");
line(13,275,42,275);
line(13,275,13,290);
line(42,275,42,290);
line(13,290,42,290);
setcolor(0);
outtextxy(500,435,"Rectangle ......");

}
//********************* FOr REcTAnglE FunTion ************************
void srectangle(int x1,int y1, int x2, int y2)
{
char key1, key2;
int a=0;
setcolor(7);
outtextxy(500,435,"Rectangle ......");
setcolor(0);
outtextxy(500,435,"Simple Rectangle ......");
line(13,250,42,250);
line(13,250,13,265);
setcolor(15);
line(42,250,42,265);
line(13,265,42,265);

while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
setcolor(15);
rectangle(x1,y1,x2,y2);
if (key2==72 && x2>x1 && y2>y1 ) x2-- && y2--;
if (key2==80 && x1>64 && x2<640 && y1>44 && y2<408) x2++ && y2++;
if (key2==59) a++;
setcolor(a);
rectangle(x1,y1,x2,y2);
}
}
setcolor(7);
outtextxy(500,435,"Simple Rectangle ......");
line(13,250,42,250);
line(13,250,13,265);
line(42,250,42,265);
line(13,265,42,265);
setcolor(0);
outtextxy(500,435,"Rectangle ......");
}
////////***********************main rectangle*************/////////
void myrectangle(int x,int y)
{
char key1, key2;
setcolor(0);
outtextxy(500,435,"Rectangle .........");
rectangle(15,254,39,262);
setfillstyle(1,0);
bar(15,278,39,286);
line(5,197,26,197);
line(5,197,5,211);
setcolor(15);
line(15,270,39,270);
line(26,197,26,211);
line(5,211,26,211);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
putpixel(x,y,15);
if (key2==72 && y>44) y--;
if (key2==80 && y<408) y++;
if (key2==75 && x>64) x--;
if (key2==77 && x<640) x++;
putpixel(x,y,0);
if (key2==59) srectangle(x,y,x,y);
if (key2==60) frectangle(x,y,x,y);
}
}
setcolor(7);
outtextxy(500,435,"Rectangle .........");
rectangle(15,254,39,262);
setfillstyle(1,7);
bar(15,278,39,286);
line(15,270,39,270);
line(5,197,26,197);
line(5,197,5,211);
line(26,197,26,211);
line(5,211,26,211);

}
//////////****************** for text Funtion**************/////
void mytext(int x ,int y )
{
char c;
char str[81];
int x1=0;
int a=0;
setcolor(0);
settextstyle(0,0,0);
outtextxy(500,435,"Text .........");
line(33,143,52,143);
line(33,143,33,165);
setcolor(15);
line(52,143,52,165);
line(33,165,52,165);
while(1)
{
c=getch();
if (c==13 || c=='\r') break;
str[x1]=c;
x1++;
str[x1]='\0';
if (c==59) a++;
setcolor(a);
settextstyle(0,0,0);
outtextxy(x,y,str);
}
setcolor(7);
settextstyle(0,0,0);
outtextxy(500,435,"Text .........");
line(33,143,52,143);
line(33,143,33,165);
line(52,143,52,165);
line(33,165,52,165);
}
///********************** FOr ERaseR FuNtiOn *****************
void myeraser(int x1,int y1, int x2, int y2 )
{
char key1, key2;
setcolor(0);
outtextxy(500,435,"Eraser .........");
line(6,73,30,73);
line(6,73,6,88);
setcolor(15);
line(30,73,30,88);
line(6,88,30,88);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
setfillstyle(1,15);
bar(x1,y1,x2+5,y2+5);
if (key2==72 && y1>44) y1-- && y2--;
if (key2==80 && y2<404) y2++ && y1++;
if (key2==75 && x1>64) x1-- && x2--;
if (key2==77 && x2<640) x2++ && x1++;
if (key2==-111 && x1+20>x2 && y1+20>y2 && x1>64 && x2<640 && y1>44 && y2<404) x2++ && y2++;
if (key2==-115 && x2>x1 && y2>y1) x2-- && y2--;
setfillstyle(1,0);
bar(x1,y1,x2+5,y2+5);
}
}
setfillstyle(1,15);
bar(x1,y1,x2+5,y2+5);
setcolor(7);
outtextxy(500,435,"Eraser .........");
line(6,73,30,73);
line(6,73,6,88);
line(30,73,30,88);
line(6,88,30,88);
}

////////for shape circle//////
void cshape(int x2,int y2)
{
char key1, key2;
int a=0;
int r=2;
setcolor(7);
outtextxy(500,435,"bold pencil .........");
setcolor(0);
outtextxy(500,435,"circle pencil .........");
line(13,273,42,273);
line(13,273,13,288);
setcolor(15);
line(42,273,42,288);
line(13,288,42,288);

while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
setcolor(a);
circle(x2,y2,r);
if (key2==59 ) a++;
if (key2==77 && x2>64) x2++;
if (key2==75 && x2<450 ) x2--;
if (key2==80 && y2<404) y2++;
if (key2==72 && y2>44) y2--;
setcolor(a);
circle(x2,y2,r);
}
}
setcolor(7);
outtextxy(500,435,"circle pencil .........");
line(13,273,42,273);
line(13,273,13,288);
line(42,273,42,288);
line(13,288,42,288);
setcolor(0);
outtextxy(500,435,"bold pencil .........");
}
/////FOR SHAPE//////
void rshape(int x1,int y1, int x2, int y2 )
{
char key1, key2;
int a=0;
setcolor(7);
outtextxy(500,435,"bold pencil .........");
setcolor(0);
outtextxy(500,435,"rshape pencil .........");
line(13,250,42,250);
line(13,250,13,264);
setcolor(15);
line(42,250,42,264);
line(13,264,42,264);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
setfillstyle(1,a);
bar(x1,y1,x2+2,y2+2);
if (key2==59 ) a++;
if (key2==72 && y1>44) y1-- && y2--;
if (key2==80 && y2<404) y2++ && y1++;
if (key2==75 && x1>64) x1-- && x2--;
if (key2==77 && x2<640) x2++ && x1++;
if (key2==-111 && x1+10>x2 && y1+10>y2 && x1>64 && x2<640 && y1>44 && y2<404) x2++ && y2++;
if (key2==-115 && x2>x1 && y2>y1) x2-- && y2--;
setfillstyle(1,a);
bar(x1,y1,x2+2,y2+2);
}
}
setcolor(7);
outtextxy(500,435,"rshape pencil .........");
line(13,250,42,250);
line(13,250,13,264);
line(42,250,42,264);
line(13,264,42,264);
setcolor(0);
outtextxy(500,435,"bold pencil .........");
}
/////////for main shape ///////////
void myshape(int x,int y)
{
char key1, key2;
setcolor(0);
outtextxy(500,435,"bold pencil .........");
setfillstyle(1,0);
bar(17,254,24,260);
bar(28,255,32,259);
bar(36,256,38,258);
circle(20,280,4);
floodfill(20,280,0);
circle(31,280,2);
floodfill(31,280,0);
circle(38,280,1);
floodfill(38,280,0);
line(30,118,30,138);
line(30,118,52,118);
setcolor(15);
line(15,268,40,268);
line(52,118,52,138);
line(30,138,52,138);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
putpixel(x,y,15);
if (key2==72 && y>44) y--;
if (key2==80 && y<408) y++;
if (key2==75 && x>64) x--;
if (key2==77 && x<640) x++;
putpixel(x,y,0);
if (key2==59) rshape(x,y,x,y);
if (key2==60) cshape(x,y);
}
}
setcolor(7);
outtextxy(500,435,"bold pencil .........");
setfillstyle(1,7);
bar(17,254,24,260);
bar(28,255,32,259);
bar(36,256,38,258);
circle(20,280,4);
floodfill(20,280,7);
circle(31,280,2);
floodfill(31,280,7);
circle(38,280,1);
floodfill(38,280,7);
line(30,118,30,138);
line(30,118,52,118);
line(15,268,40,268);
line(52,118,52,138);
line(30,138,52,138);
}

//////for pencil////////
void mypencil(int x,int y)
{
char key1,key2;
int a=0;
setcolor(0);
outtextxy(500,435,"simple pencil .........");
line(6,118,6,138);
line(6,118,28,118);
setcolor(15);
line(28,118,28,138);
line(6,138,28,138);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
putpixel(x,y,a);
if (key2==72 && y>44) y--;
if (key2==80 && y<404) y++ ;
if (key2==75 && x>64) x--;
if (key2==77 && x<640) x++;
if (key2==59) a++;
putpixel(x,y,a);
}
}
setcolor(7);
outtextxy(500,435,"simple pencil .........");
line(6,118,6,138);
line(6,118,28,118);
line(28,118,28,138);
line(6,138,28,138);
}
void spere(int x, int y)
{
int a;
randomize();
while(1)
{ if (kbhit())break;
for(a=50; a<70; a++)
{
    delay(10);
    x=random(20);
    y=random(20);
    putpixel(x,y,3);
}
}
getche();
}
/////////****************for ccrectanle******************///////////
void ccrectangle(int x1, int x2, int y1 ,int y2 ,int y3,int r1,int r2)
{
char key1, key2;
int a=0;
setcolor(7);
outtextxy(500,435,"C.Rectangle ......");
setcolor(0);
outtextxy(480,435,"Fill C.Rectangle ......");
line(13,273,42,273);
line(13,273,13,288);
setcolor(15);
line(42,273,42,288);
line(13,288,42,288);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
if (key2==59) a++;
if (key2==72 && y2>y1) y2-- && y1++ && r2-- ;
if (key2==80 ) y1-- && y2++ && r2++ ;
if (key2==75 && x2>x1) x2-- && x1++ && r1-- ;
if (key2==77 ) x1-- && x2++ && r1++ ;
setcolor(a);
line(x1,y1,x2,y1);
line(x1,y2,x2,y2);
ellipse(x2,y3,270,90,r1,r2);
ellipse(x1,y3,90,270,r1,r2);
}
}
setcolor(7);
outtextxy(480,435,"Fill C.Rectangle ......");
line(13,273,42,273);
line(13,273,13,288);
line(42,273,42,288);
line(13,288,42,288);
setcolor(0);
outtextxy(500,435,"C.Rectangle ......");
}
/////////****************for screctanle******************///////////
void screctangle(int x1, int x2, int y1 ,int y2 ,int y3,int r1,int r2)
{
char key1, key2;
int a=0;
setcolor(7);
outtextxy(500,435,"C.Rectangle ......");
setcolor(0);
outtextxy(480,435,"Simple C.Rectangle ......");
line(13,250,42,250);
line(13,250,13,266);
setcolor(15);
line(42,250,42,266);
line(13,266,42,266);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
setcolor(15);
line(x1,y1,x2,y1);
line(x1,y2,x2,y2);
ellipse(x2,y3,270,90,r1,r2);
ellipse(x1,y3,90,270,r1,r2);
if (key2==59) a++;
if (key2==72 && y2>y1) y2-- && y1++ && r2-- ;
if (key2==80 ) y1-- && y2++ && r2++ ;
if (key2==75 && x2>x1) x2-- && x1++ && r1-- ;
if (key2==77 ) x1-- && x2++ && r1++ ;
setcolor(a);
line(x1,y1,x2,y1);
line(x1,y2,x2,y2);
ellipse(x2,y3,270,90,r1,r2);
ellipse(x1,y3,90,270,r1,r2);
}
}
setcolor(7);
outtextxy(480,435,"Simple C.Rectangle ......");
line(13,250,42,250);
line(13,250,13,266);
line(42,250,42,266);
line(13,266,42,266);
setcolor(0);
outtextxy(500,435,"C.Rectangle ......");
}

////////***************for main crectangle****************//////
void crectangle(int x1, int x2, int y1 ,int y2 ,int y3,int r1,int r2)
{
char key1, key2;
setcolor(0);
outtextxy(500,435,"C.Rectangle ......");
line(18,253,36,253);
line(18,263,36,263);
ellipse(36,258,270,90,2,4);
ellipse(18,258,90,270,2,4);
line(18,275,36,275);
line(18,285,36,285);
ellipse(36,280,270,90,2,4);
ellipse(18,280,90,270,2,4);
setfillstyle(1,0);
floodfill(36,280,0);
line(30,214,50,214);
line(30,214,30,228);
setcolor(15);
line(15,270,38,270);
line(50,214,50,228);
line(30,228,50,228);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
setcolor(15);
if (key2==59) screctangle(x1,x2,y1,y2,y3,r1,r2);
if (key2==60) ccrectangle(x1,x2,y1,y2,y3,r1,r2);
}
}
setcolor(7);
outtextxy(500,435,"C.Rectangle ......");
line(18,253,36,253);
line(18,263,36,263);
ellipse(36,258,270,90,2,4);
ellipse(18,258,90,270,2,4);
line(18,275,36,275);
line(18,285,36,285);
ellipse(36,280,270,90,2,4);
ellipse(18,280,90,270,2,4);
setfillstyle(1,7);
floodfill(36,280,7);
line(15,270,38,270);
line(30,214,50,214);
line(30,214,30,228);
line(50,214,50,228);
line(30,228,50,228);
}
//////for myellipse////////
void myellipse(int x,int y)
{
char key1,key2;
int a=0;
int r1=0,r2=0;
setcolor(0);
outtextxy(500,435,"simple ellipse .........");
line(6,118,6,138);
line(6,118,28,118);
setcolor(15);
line(28,118,28,138);
line(6,138,28,138);
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
setcolor(15);
ellipse(x,y,1,180,r1,r2);
if (key2==77) r1++;
if (key2==72) r2++;
setcolor(0);
ellipse(x,y,1,180,r1,r2);
if (key2==59) a++;
}
}
setcolor(7);
outtextxy(500,435,"simple ellipse .........");
line(6,118,6,138);
line(6,118,28,118);
line(28,118,28,138);
line(6,138,28,138);
}
//************************* for help Bar *************************
void myhelp()
{
void *img1;
unsigned size;
size=imagesize(252,42,362,92);
img1=(void *) malloc(size);
getimage(250,40,363,93,img1);
setfillstyle(1,7);
bar(252,42,362,92);
setfillstyle(1,15);
bar(250,40,360,90);
setcolor(0);
settextstyle(2,0,0);
outtextxy(258,45," Help Topics ");
outtextxy(258,70," About Paint ");
setcolor(7);
line(250,65,360,65);
getche();
putimage(250,40,img1,COPY_PUT);
}
//************************* for color Bar *************************
void mycolor()
{
void *img1;
unsigned size;
size=imagesize(202,42,302,62);
img1=(void *) malloc(size);
getimage(200,40,303,63,img1);
setfillstyle(1,7);
bar(202,42,302,62);
setfillstyle(1,15);
bar(200,40,300,60);
setcolor(0);
settextstyle(2,0,0);
outtextxy(208,45,"Edit Color.... ");
getch();
putimage(200,40,img1,COPY_PUT);
}
//************************* for image Bar *************************
void myimage()
{
void *img1;
unsigned size;
size=imagesize(152,42,332,132);
img1=(void *) malloc(size);
getimage(150,40,333,133,img1);
setfillstyle(1,7);
bar(152,42,332,132);
setfillstyle(1,15);
bar(150,40,330,130);
setcolor(0);
settextstyle(2,0,0);
outtextxy(158,45,"Flip/rotate... Ctrl+R");
outtextxy(158,60,"StretchSkew... Ctrl+W");
outtextxy(158,75,"Invert Colors Ctrl+I");
outtextxy(158,90,"attributes... Ctrl+E");
outtextxy(158,113,"clear Image Ctrl+shFt+N");
getch();
putimage(150,40,img1,COPY_PUT);
}
//************************* for view Bar *************************
void myview()
{
void *img1;
unsigned size;
size=imagesize(102,42,252,132);
img1=(void *) malloc(size);
getimage(100,40,253,133,img1);
setfillstyle(1,7);
bar(102,42,252,132);
setfillstyle(1,15);
bar(100,40,250,130);
setcolor(0);
settextstyle(2,0,0);
outtextxy(105,45,"Tool box ctrl+T");
outtextxy(105,60,"color box ctrl+L");
outtextxy(105,75,"status bar ");
outtextxy(105,90,"Text Toolbar ");
outtextxy(105,113,"View Bitmap ctrl+F");
setcolor(7);
line(100,108,250,108);
getch();
putimage(100,40,img1,COPY_PUT);
}
//************************* for edit Bar *************************
void fedit()
{
void *img1;
unsigned size;
size=imagesize(52,42,182,132);
img1=(void *) malloc(size);
getimage(50,40,183,133,img1);
setfillstyle(1,7);
bar(52,42,182,132);
setfillstyle(1,15);
bar(50,40,180,130);
setcolor(0);
settextstyle(2,0,0);
outtextxy(55,45,"Cut ctrl+X");
outtextxy(55,60,"Copy ctrl+C");
outtextxy(55,75,"paste ctrl+V");
outtextxy(55,90,"Select All ctrl+A");
outtextxy(55,113,"Undo ctrl+Z");
setcolor(7);
line(50,108,180,108);
getch();
putimage(50,40,img1,COPY_PUT);
}
void save()
{ struct save
{

}r;

FILE *fp;
unsigned size;
size=imagesize(2,42,122,132);
fp=(FILE *) malloc(size);
getimage(0,40,123,133,fp);


fp=fopen("xee.dbf", "a");
fwrite(&r,sizeof(r),1,fp);
fclose(fp);

}
//************************* for file Bar *************************
void myfile()
{
void *img1;
unsigned size;
size=imagesize(2,42,122,132);
img1=(void *) malloc(size);
getimage(0,40,123,133,img1);
setfillstyle(1,7);
bar(2,42,122,132);
setfillstyle(1,15);
bar(0,40,120,130);
setcolor(0);
settextstyle(2,0,0);
outtextxy(5,45,"New ctrl+N");
outtextxy(5,60,"Open ctrl+O");
outtextxy(5,75,"Save ctrl+S");
outtextxy(5,90,"Save As ");
outtextxy(5,113,"Exit Alt+F4");
setcolor(7);
line(0,108,120,108);
getch();
putimage(0,40,img1,COPY_PUT);
}
void mycolorbar(int x, int y, int a)
{
char key1, key2;
void *img1;
unsigned size;
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
if (key2==59) a++;
putpixel(x,y,15);
putimage(x,y,img1,XOR_PUT);
if (key2==72 && y>44) y--;
if (key2==80 && y<408) y++;
if (key2==75 && x>64) x--;
if (key2==77 && x<640) x++;
putpixel(x,y,0);
size=imagesize(x,y,x,y);
img1=(void *) malloc(size);
getimage(x,y,x,y,img1);
if (key2==59) a++;
setcolor(a);
setfillstyle(1,a);
floodfill(x,y,a);

}
}
}
//************************* for funtion Control *************************
void mycontrol()
{
char key1, key2;
setcolor(0);
outtextxy(500,435,"My control ......");
while(1)
{
key1=getch();
if(key1==13) break;
if(key1==0)
{
key2=getch();
if (key2==59) myfile();
if (key2==60) fedit();
if (key2==61) myview();
if (key2==62) myimage();
if (key2==63) mycolor();
if (key2==64) myhelp();
}
}
setcolor(7);
outtextxy(500,435,"My control ......");
}
//************************* for paint brush Control *************************
void brush()
{
char key1, key2;
int x=340,y=230,a=0;
int e[20],f[20];
design();
putpixel(x,y,0);
while(1)
{
key1=getch();
if(key1==27) exit(0);
if(key1==0)
{
key2=getch();

if (key2==44) myrectangle(x,y);
if (key2==45) myshape(x,y);
if (key2==46) mycircle(x,y);
if (key2==47) crectangle(x,x,y,y,y,1,0);
if (key2==48) mytext(x,y);
if (key2==49) myeraser(x,y,x,y);
if (key2==50) mypencil(x,y);
if (key2==59) a++;
if (key2==61){cleardevice(); helpf();}
if (key2==60) mycolorbar(x,y,a);
if (key2==65)  save();
if (key2==-115 && y>44) y--;
if (key2==-111 && y<408) y++;
if (key2==115 && x>64) x--;
if (key2==116 && x<640) x++;
putpixel(x,y,15);
}
if (key2==72 && y>44) y--;
if (key2==80 && y<408) y++;
if (key2==75 && x>64) x--;
if (key2==77 && x<640) x++;
putpixel(x,y,a);
}
}
//******************** for Loading PaGe ********************
void loading()
{
setcolor(15);
settextstyle(0,0,1);
outtextxy(200,357,"Paint Box Loading .......");
int i,j;
for(j=1; j<360; j++)
{
for(i=1; i<25; i++)
{
setcolor(2);
ellipse(300,250,90,90+j,60+i,60+i);
setcolor(15);
ellipse(300,250,90,90+j,60,60);
ellipse(300,250,90,90+j,85,85);
}
}
}
void main()
{
int d,m;
d=VGA;
m=VGAHI;

initgraph(&d,&m,"c:\\Tc\\BGI");
title();
loading();
brush();
}

